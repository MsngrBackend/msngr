# Common commands

## Update all submodules to latest remote
  ```git submodule update --remote --merge```

## Update a specific submodule only
  ```git submodule update --remote --merge auth-service```

## Pull changes after someone else updated submodule pointers
  ```git submodule update --init --recursive```

## See which submodules have new commits available
  ```git submodule status```
