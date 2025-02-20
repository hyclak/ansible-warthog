# Role: warthog_node

This role is responsible for setting up a Warthog Node.

## Requirements

- systemd-based Linux Distribution

## Role Variables

| Variable Name                   | Default value                                                  | Description                      |
|---------------------------------|----------------------------------------------------------------|----------------------------------|
| `warthog_node__git_release_url` | <https://github.com/warthog-network/Warthog/releases/download> | URL to Warthog Releases          |
| `warthog_node__node_version`    | 0.8.6                                                          | Warthog Version                  |
| `warthog_node__public_node`     | true                                                           | Enable Public Node functionality |
| `warthog_node__warthog_dir`     | /opt/warthog                                                   | Directory to install node executable |
| `warthog_node__warthog_user`    | { name: "warthog", uid: "923" }                                  | Local user to create to run the node. Dictionary of name, uid. |

## Dependencies

None

## License

MIT

## Author Information

Matthew Hyclak - <hyclak@gmail.com>
