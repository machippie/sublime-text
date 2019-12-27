
## Default Variables

### sublime_text_started

Restart app if already running

#### Default value

```yaml
sublime_text_started: true
```

### sublime_text_user

User to run user-specific commands

#### Default value

```yaml
sublime_text_user | default(homebrew_user) | default(ansible_user_id)
```
## Dependencies

None

## License

Apache-2.0

## Author

Thomas Boerger
