# Boogeyman
A simple and blazingly fast unit conversion API powered by Rust

# Usage

This is an example of how to use the API.

```bash
curl -s "http://127.0.0.1:8080/temperature?val=50&from=c&to=f" | jq
```

That command will send an API request to the server for converting
the given value (`50`) from the `celsius` unit to the `fahrenheit` unit.
The result for that command will look like:

```json
{
  "from": "c",
  "to": "f",
  "val": 50.0,
  "res": 122.0
}
```

# License

Licensed under either of

- Apache License, Version 2.0 ([LICENSE-APACHE](LICENSE-APACHE) or <https://www.apache.org/licenses/LICENSE-2.0>)
- MIT License ([LICENSE-MIT](LICENSE-MIT) or <https://opensource.org/licenses/MIT>)

at your option.

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in this project by you, as defined in the Apache-2.0 license,
shall be dual licensed as above, without any additional terms or conditions.

Copyright © 2026 Farhan Kurnia Pratama
