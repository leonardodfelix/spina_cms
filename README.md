# Spina CSM

### Project setup:

```bash
rails new spina_csm -j esbuild -c tailwind -d postgresql
```

### Add gems:

- foreman
- spina

### Spina setup:

```bash
rails g spina:install
rails active_storage:install
rails db:migrate
```

[Spina docs](https://spinacms.com/docs)

[Spina github](https://github.com/spinacms/spina)
