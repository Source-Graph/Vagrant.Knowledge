https://superuser.com/questions/756758/is-it-possible-to-disable-default-vagrant-synced-folder

```
Vagrant.configure('2') do |config|
  config.vm.synced_folder '.', '/vagrant', disabled: true
  # ...
end
```
