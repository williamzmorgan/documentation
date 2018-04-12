# Publish

When you have finished to create your [service file](https://github.com/mesg-foundation/documentation/tree/b3d92737e4dfd41f30e20d0ab1f2b8dbbf045a2d/service/configuration.md), [validate it](https://github.com/mesg-foundation/documentation/tree/b3d92737e4dfd41f30e20d0ab1f2b8dbbf045a2d/service/validation.md) and [test it](test.md), you are ready to publish it.

Each publication will cost you a small amount of token. Be aware this amount is **not refundable.** So please make sure to test your service correctly.

To publish a service, run the command:

```bash
mesg-cli service publish
```

If you don't set the path to the service folder, the method looks in the current folder for the `mesg.yml` file.

The first time you publish the service, it will be publish as a new service and an unique service Id will be created. This Id will be saved in a `.mesg` file.

When publishing an already published service \(when a `.mesg` file containing the service Id exist\), the service will be updated on the Network. Users that use this service, will have to manually update their workflow to use the last version of the service.

A version Id is created every time you publish the service. This version id is also saved in the `.mesg` file\).
