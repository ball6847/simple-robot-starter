Simple Robot Starter
====================

Simple starter for robot framework and selenium for web testing

Setup
-----

After cloning the repository, run this command

```
# first time only
direnv allow

# then wait until direnv finish virtualenv setup
```

Then write a test suite lets say `example.robot` and run the following command

```
robot example.robot
```

All output such as reports, logs and screenshot will be saved to `output` directory
