# X-Camp Contest Policies

Policy pages for X-Camp contest rewards. These pages tell students and parents the rules.

Your site is live at
**https://x-camp-academy-ca.github.io/xcamp-contest-policies/**

## Pages

| Policy | Page | URL |
|---|---|---|
| Credit redemption | X-Camp 在读学生竞赛奖励兑换政策 | [open](https://x-camp-academy-ca.github.io/xcamp-contest-policies/xcamp-credit-redemption-policy.html) |

The credit redemption page is in Chinese. It tells current X-Camp students how to redeem a
contest award.

## File names

Use this pattern for a new page:

```
xcamp-{topic}-policy.html
```

- Write all characters in lower case. Use a hyphen between words.
- Use the word `policy`. Do not use `poster` or `rules`.
- Do not add a version number to the file name. Git keeps the history.

## Google Analytics

Each page has the Google Analytics tag `G-L64HE50P6M` in the `<head>` block. Copy this
block into each new page:

```html
<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-L64HE50P6M"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-L64HE50P6M');
</script>
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
```

Google keeps this data for 30 days only. Download a report before the data expires.
