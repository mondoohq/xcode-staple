___This is an work of devbotsxyz, who's account is now removed from GitHub.  We appreciate his contribution to the community!___

# Xcode Staple

This Action staples notary service tickets to macOS products.

## Basic Usage

```yaml
- name: "Staple Release Build"
  uses: devbotsxyz/xcode-staple@v1
  with:
    product-path: "Export/Application.app"
```

## Full Example

The [devbotsxyz/example-macos-rings](https://github.com/devbotsxyz/example-macos-rings) project is an example macOS project with a [release.yml](https://github.com/devbotsxyz/example-macos-rings/.github/workflows/release.yml) workflow that shows all the steps needed to go from creating a release in GitHub to ending up with a `.zip` file that contains a signed and notarized application.

## Related Actions

 * [Carthage Bootstrap](https://github.com/marketplace/actions/xcode-staple) - Bootstrap your Carthage Dependencies/
 * [Xcode Staple](https://github.com/marketplace/actions/xcode-staple) - Staple a Notarization Ticket to your product.

## License and Contributions

This Action is licensed under the [MIT](LICENSE) license. Contributions are very much welcome and encouraged but we would like to ask to file an issue before submitting pull requests. 
