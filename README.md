# mandrillex

a Mandrill wrapper for Elixir

## Usage

```elixir
iex> Mandrillex.start
:ok

iex(2)> Mandrillex.key
"your_key"

iex(3)> Mandrillex.Users.info
[username: "your_username", created_at: "2013-12-05 00:24:19.47554",
 public_id: "your_public_id", reputation: 0, hourly_quota: 25,
 backlog: 0,
 stats: [today: [sent: 0, hard_bounces: 0, soft_bounces: 0, rejects: 0,
   complaints: 0, unsubs: 0, opens: 0, unique_opens: 0, clicks: 0,
   unique_clicks: 0],
  last_7_days: [sent: 0, hard_bounces: 0, soft_bounces: 0, rejects: 0,
   complaints: 0, unsubs: 0, opens: 0, unique_opens: 0, clicks: 0,
   unique_clicks: 0],
  last_30_days: [sent: 0, hard_bounces: 0, soft_bounces: 0, rejects: 0,
   complaints: 0, unsubs: 0, opens: 0, unique_opens: 0, clicks: 0,
   unique_clicks: 0],
  last_60_days: [sent: 0, hard_bounces: 0, soft_bounces: 0, rejects: 0,
   complaints: 0, unsubs: 0, opens: 0, unique_opens: 0, clicks: 0,
   unique_clicks: 0],
  last_90_days: [sent: 0, hard_bounces: 0, soft_bounces: 0, rejects: 0,
   complaints: 0, unsubs: 0, opens: 0, unique_opens: 0, clicks: 0,
   unique_clicks: 0],
  all_time: [sent: 0, hard_bounces: 0, soft_bounces: 0, rejects: 0,
   complaints: 0, unsubs: 0, opens: 0, unique_opens: 0, clicks: 0,
   unique_clicks: 0]]]

iex> Mandrillex.Users.info[:username]
"your_username"
```

## Dependencies

- [HTTPoison](https://github.com/edgurgel/httpoison)
- [JSEX](https://github.com/talentdeficit/jsex)

## License

See [LICENSE](https://github.com/slogsdon/mandrillex/blob/master/LICENSE)