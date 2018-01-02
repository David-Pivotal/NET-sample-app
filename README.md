# .NET Sample App

Push the app with no-start:
```
cf push environment -s windows2012R2 -b hwc_buildpack ./ViewEnvironment/
```

Once your app is pushed, you can navigate to the app's URL and you will
see all the VCAP variables.  Add ?all= to get all the system variables
too.

After your first push, you can simply push your updates without any additional command line arguments:

```
cf push environment
```
