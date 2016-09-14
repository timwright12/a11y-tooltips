# Accessible Tooltips

This plugin was converted from a jQuery plugin originally written by [@scottohara](https://github.com/scottaohara/). You can view the original code in [Scott's Accessible Component Library](https://github.com/scottaohara/accessible-components). Pretty much everything is the same, you just don't need jQuery.

It was created to help you implement accessible tooltips with minimal work, because everyone is tired of using crappy UI plugins that damage the underlying experience. [Check out the demo](https://timwright12.github.io/a11y-tooltips/)

## Example HTML You'll Need

```html
<!-- Hover to expose the tooltip -->

<span class="a11y-tip">
  <span class="a11y-tip__trigger">
    Tooltip Trigger span
  </span>

  <span class="a11y-tip__help">
    Tooltip content goes here
  </span>
</span><!--/.a11y-tip-->

<!-- Click to expose the tooltip -->

<span class="a11y-tip a11y-tip--toggle">
  <span class="a11y-tip__trigger">
    Tooltip Toggle Trigger
  </span>

  <span class="a11y-tip__help">
    Tooltip content goes here
  </span>
</span><!--/.a11y-tip-->
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b feature/my-new-feature`
3. Commit your changes: `git commit -m 'Added some great feature!'`
4. Push to the branch: `git push origin feature/my-new-feature`
5. Submit a pull request

## Credits

- [Scott O'Hara](https://github.com/scottaohara/) ( [@scottohara](https://twitter.com/scottohara) )
- [Tim Wright](http://github.com/timwright12) ( [@csskarma](http://twitter.com/csskarma) )

## License

Code and documentation are released under the MIT license.

## Browser support

| Feature       | Chrome | Firefox | Internet Explorer | Safari |
|---------------|--------|---------|-------------------|--------|
| Basic Support | Latest | Latest  | 9+                | 5.1+   |
