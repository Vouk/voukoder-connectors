## Latest versions
- [premiere-connector-1.2.0.msi](premiere/premiere-connector-1.2.0.msi?raw=true) [(Changelog)](premiere/README.md)
- [aftereffects-connector-0.9.3.msi](aftereffects/aftereffects-connector-0.9.3.msi?raw=true) [(Changelog)](aftereffects/README.md)
- [vegas-connector-0.6.0.msi](vegas/vegas-connector-0.6.0.msi?raw=true) [(Changelog)](vegas/README.md)

## Support
If you have questions or suggestions please check out the official [forum](https://www.voukoder.org/forum/).

## What are these connectors for?
Since version 2.3 the Voukoder project has significantly changed. It is not one monolothic component anymore, it has been split into two components:
1. The [Voukoder Core](https://github.com/Vouk/voukoder) component will be registered as a system wide COM server and will provide its encoding services and user interface to as many programs as possible. You can even integrate it to your own program.
2. The **connector**. A connector is the component that binds to the host application and sends the frame data to the voukoder core component.

## Why so complicated? I liked it how it was before!
This step was necessary for many reasons and was actually unavoidable:
- Clear separation between proprietary and open source code
- One voukoder component serves many connectors
- Possible future features (i.e. self updating)
- ...

In fact the connectors will most likely not change that often. You just need to install the latest voukoder core component in case of an update, just as before.

## Note
These connectors require [voukoder 2.3 or later](https://github.com/Vouk/voukoder/releases). Please uninstall previous versions before updating first.
