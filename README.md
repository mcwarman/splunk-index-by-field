# splunk-index-by-field

Splunk app which clones data from one index to another based on field value.

## Running

```
docker-compose up
```

## Testing

To test there are two user accounts (`user1`, `user2`) these accounts have been assigned roles (`index1_all`, `index1_warn`) the roles have different values set for `srchIndexesAllowed`:

1. Logon with account (password: `password`)
2. Navigate to dashboard: http://localhost:8000/en-GB/app/index-by-field/dashboard
