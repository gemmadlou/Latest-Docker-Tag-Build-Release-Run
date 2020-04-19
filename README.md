# Latest Docker Tag: 🏨 Build, 📔 Release, 🚀 Run

## Usage

- Copy the project
- Setup the `container` property in the `package.json`. Use the example one for more information.
- Create your Dockerfile
- Add the bin scripts to your project
- Update the `bin/run` to suit your project. This was made with Laravel in mid.

```bash
# Build your image
bin/build

# Publish your image
bin/publish

# Run your image and check http://localhost:3001
bin/run
```
