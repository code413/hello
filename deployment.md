This is a checklist for us to run through before we deploy projects live.

# For Projects on cPanel
- [ ] [Force SSL and redirect non-www to www](https://gist.github.com/matt-daneshvar/a97fc176a2c450d5770e623384075d51)
- [ ] [Update Linux file permissions after pulling from a git repo](https://gist.github.com/matt-daneshvar/3a68ad9d1a40314408c37b2ca4d1cda3)

# For Laravel Projects
- [ ] Clear cache. 
```bash
php artisan dump-autoload
php artisan cache:clear
php artisan view:clear
php artisan config:cache
```

# For WordPress Projects
- [ ] Install SEO tools (We use Yoast SEO on most projects).

# Tracking
- [ ] Install GTM.
