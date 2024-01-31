# feed-rs
A simple feed parser (RSS, Atom, JSON Feed)

The parser library is in feed-rs, with a simple test tool in testurls

### Disclaimer

this is not the original version, this is a forked 1.4.0 version made just for personal purpose, I'd like to rustlerize it for Elixir purposes, but I need serde_json to do it, so I brutally *#[derive(Serialize, Deserialize)]*'d it, crippling the mime things around the library ('cause Mime too does not have serde feature flags).

so, you don't want this lib, please check the original library at https://github.com/feed-rs/feed-rs (a very nice work made by serious people)
