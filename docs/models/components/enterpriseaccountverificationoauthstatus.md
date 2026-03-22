# EnterpriseAccountVerificationOauthStatus

## Example Usage

```ruby
require "dctest-sdk-ruby"

value = EnterpriseAccountVerificationOauthStatus::UNVERIFIED

# Open enum: use .deserialize() to create instances from custom string values
custom = EnterpriseAccountVerificationOauthStatus.deserialize("custom_value")
```


## Values

| Name           | Value          |
| -------------- | -------------- |
| `UNVERIFIED`   | unverified     |
| `VERIFIED`     | verified       |
| `FAILED`       | failed         |
| `EXPIRED`      | expired        |
| `TRANSFERABLE` | transferable   |