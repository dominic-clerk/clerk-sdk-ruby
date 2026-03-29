# OauthConfig

Present when the enterprise connection uses OIDC


## Fields

| Field                                                                | Type                                                                 | Required                                                             | Description                                                          |
| -------------------------------------------------------------------- | -------------------------------------------------------------------- | -------------------------------------------------------------------- | -------------------------------------------------------------------- |
| `id`                                                                 | *Crystalline::Nilable.new(::String)*                                 | :heavy_minus_sign:                                                   | OAuth config ID                                                      |
| `name`                                                               | *Crystalline::Nilable.new(::String)*                                 | :heavy_minus_sign:                                                   | Custom OIDC provider display name                                    |
| `provider_key`                                                       | *Crystalline::Nilable.new(::String)*                                 | :heavy_minus_sign:                                                   | OAuth provider key (e.g. oidc_custom, oidc_ghe_*, oidc_gitlab_ent_*) |
| `client_id`                                                          | *Crystalline::Nilable.new(::String)*                                 | :heavy_minus_sign:                                                   | OAuth client ID                                                      |
| `discovery_url`                                                      | *Crystalline::Nilable.new(::String)*                                 | :heavy_minus_sign:                                                   | OIDC discovery URL                                                   |
| `logo_public_url`                                                    | *Crystalline::Nilable.new(::String)*                                 | :heavy_minus_sign:                                                   | Logo URL for the provider                                            |
| `created_at`                                                         | *Crystalline::Nilable.new(::Integer)*                                | :heavy_minus_sign:                                                   | Unix timestamp in milliseconds when the config was created           |
| `updated_at`                                                         | *Crystalline::Nilable.new(::Integer)*                                | :heavy_minus_sign:                                                   | Unix timestamp in milliseconds when the config was last updated      |