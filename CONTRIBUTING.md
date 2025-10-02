We encourage contributions that continue to address the intended audience and
design of this project. Bear in mind that this is primarily a teaching tool for
using Git together with Godot, and so has a deliberately narrow scope.

### Development environment

Please use [pre-commit](https://pre-commit.com) to check for correct formatting
and other issues before creating commits. To do this automatically, you can add
it as a git hook:

```
# If you don't have pre-commit already:
pip install pre-commit

# Setup git hook:
pre-commit install
```

Now `pre-commit` will run automatically on `git commit`!
