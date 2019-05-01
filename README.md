# Ansible role 'ansible-role-tmux'

An Ansible role for setting up tmux.

## Requirements
Only tested on Fedora, but might very well work for quite a few other distros. Feel free to provide feedback.

## Role Variables
| Variable		| Default		| Comments (type) |
| :---			| :---			| :---		  |
| `tmux_pline_path` | `/usr/share` | Might vary with different distros. If so, add in vars/<dist>.yml | 

## Dependencies

## Example Playbook
```Yaml
- hosts: foo
  roles:
    - role: ansible-role-tmux
```

## Testing


## License

BSD

## Contributors

Issues, feature requests, ideas, suggestions, etc. are appreciated and can be posted in the Issues section. Pull requests are also very welcome. Please create a topic branch for your proposed changes, it's the easiest way to merge back into the project.

- [Oscar Petersson](https://github.com/oscpe262/) (Maintainer)
