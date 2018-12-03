This is a checklist for us to run through before we deploy projects live.

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
