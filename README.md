# Brightbox Ruby

Installs ruby from apt repo maintained by Brightbox.

This also installs ruby-switch to switch between ruby versions.

## Role Variables

    - brightbox_ruby_version: 2.3
    - brightbox_ruby_gems:
        - bundler
        - foreman

## Example

    - hosts: app
      vars:
        brightbox_ruby_version: 2.3
      roles:
        brightbox-ruby

## License

MIT
