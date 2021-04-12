
# Drop Caps

```
// Unfortunately most browsers do fake small caps still.
// So use a typeface with a dedicated small caps font.

// OR Try font-feature settings
// https://stackoverflow.com/questions/13110272/enabling-small-capitals
// http://webtypography.net/3.2.2

abbr,
.sc {
  -moz-font-feature-settings: 'smcp';
  -webkit-font-feature-settings: 'smcp';
  -ms-font-feature-settings: 'smcp';
  font-feature-settings: 'smcp';
  font-variant-numeric: oldstyle-nums; // lining numbers look weird in small caps
}
```