# Changelog


## 0.7.1

* Added `:otp_app` config parameter.


## 0.7.0

* Simplified outgoing HTTP code by removing keepalive.


## 0.6.3

* Removed Timex dependency.
  Thanks [@mindreframer](https://github.com/mindreframer)!

* Fixed handling of port numbers in DSN URL.
  Thanks [@mindreframer](https://github.com/mindreframer)!

* Updated dev dependency ExSpec to 2.0.


## 0.6.2

* Refactored to send all requests directly from ExSentry.Client, rather
  than spawning a process for each request.


## 0.5.1

* Added Elixir 1.3 compatibility.
  Thanks [@cschiewek](https://github.com/cschiewek)!


## 0.5.0

* Added `:stacktrace` option to `ExSentry.capture_exception`.

* Added `:exception_whitelist` and `:plug_status_whitelist` options
  to `ExSentry.Plug`.


## 0.4.0

* Fixed error around `String.Graphemes.next_grapheme_size`.

* Added `ExSentry.LoggerBackend`, for sending log messages to Sentry.


## 0.3.0

* Prevent ExSentry itself from ever raising an exception due to user
  input.


## 0.2.2

* Updated Timex and adjusted HTTPoison code. Thanks
  [@gshaw](https://github.com/gshaw)!

* Relaxed Poison version constraint.
  Thanks [@zacharydenton](https://github.com/zacharydenton)!

* Support `SENTRY_DSN` environment variable in `ExSentry.Client`.
  Thanks [@shiroyasha](https://github.com/shiroyasha)!


## 0.2.1

Last release as a single-programmer project.

