## Note:
These connectors requires voukoder 2.3beta2 or later.

## Latest versions
- [adobe-premiere-connector-0.9.1.msi](adobe-premiere/adobe-premiere-connector-0.9.1.msi?raw=true)
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

**I'd like to create a special installer program that makes it simpler and detects installed or not installed versions, downloads whats required. If you can help me with this please contact me at vouk@mailbox.org.**
