
# Install the boost ansible role

```bash
# Create a directory for the ansible role. 
install -d ~/.ansible/roles/computate.computate_boost

# Clone the boost ansible role. 
git clone git@github.com:computate-org/computate_boost.git ~/.ansible/roles/computate.computate_boost

# Change into the boost ansible role directory. 
cd ~/.ansible/roles/computate.computate_boost
```

# Run the boost ansible playbook to install boost locally. 

```bash
ansible-playbook install.yml
```

Christopher Tate
