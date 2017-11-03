# Roscasper
## Customising
Add the following to your ghost_foot code injection:

```
<script>
    var socialMedia = {
        'github': 'https://github.com/username',
        'linkedin': 'https://linkedin.com/in/username'
    };
    var disqusShortName = 'shortname';
    var googleAnalytics = 'analytics_id';
</script>
```

The theme will then pick up these variables and use them accordingly.
If you don't define these variables, the corresponding functions will be disabled.

# Copyright & License

Copyright (c) 2017 Rosco Kalis - Released under the [MIT license](LICENSE).
