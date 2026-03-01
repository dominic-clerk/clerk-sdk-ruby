<!-- Start SDK Example Usage [usage] -->
```ruby
require 'dctest_sdk_ruby'

Models = ::Clerk::Models
s = ::Clerk::OpenAPIClient.new(
  bearer_auth: '<YOUR_BEARER_TOKEN_HERE>'
)
res = s.email_addresses.get(email_address_id: '<id>')

unless res.email_address.nil?
  # handle response
end

```
<!-- End SDK Example Usage [usage] -->