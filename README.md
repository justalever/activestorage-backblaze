This is a gem for using backblaze with activestorage.

# Usage:

```ruby
gem 'activestorage-backblaze'
```

Then in your storage.yml, use the following

```yaml
backblaze:
  service: Backblaze
  bucket_name: <bucket_name>
  bucket_id: <bucket_id>
  account_id: <keyId>
  acount_token: <applicationKey>
```

In your environments/production.rb or application.rb (depending on your choice) add the following:

```ruby
config.active_storage.service = :backblaze
```
