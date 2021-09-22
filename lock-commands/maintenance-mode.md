# Maintenance Mode

## Maintenance Mode

One of the most popular LockBot commands, and can be very helpful as a server tool as well as a lockdown tool which some users prefer to use it as.

Maintenance mode has been a challenge to maintain but it is back, stronger as ever.

{% hint style="danger" %}
**Note: Due to the high resource usage of m-mode, we have a limit of 60 channels.**
{% endhint %}

{% hint style="success" %}
**Format: \[prefix\]m-mode**

**User Perms Required: LockBot Admin, Server Admin**

**Bot Perms Required: Manage channels, Manage messages** – _It's advised that LockBot should have the administrator permission to carry out functions correctly._
{% endhint %}

Upon the command being given, LockBot will display a notice that should be read for your information. It will also ask you if you wish to continue with the command. If you do you will need to reply “yes” \(keep in mind this is case sensitive\). If you do not reply, it will time out and cancel. This feature is in place as this command can be quite destructive if not used correctly.

![Confirmation prompt for m-mode](../.gitbook/assets/yvrpr8-1-.png)

{% hint style="warning" %}
## Issues

If there are issues \(users can still talk/view channels\) then please read the following information before going to support:

Go to `Channel Settings` -&gt; `Permissions`

All public channels that can be accessed by members:

* Set ![:GrayTick:](https://cdn.discordapp.com/emojis/452773421294813185.png?v=1)`Send Messages` for the **your members** role.

If you are still having issues then visit the discord server.
{% endhint %}







### What does this command actually do?

Once activated, this command will lock all of the server's channels using the @everyone role _\(if other roles are set to override this then it may not work correctly. However, this may be to your advantage\)._ It will also create a temporary channel with some basic info, this can be removed if desired. Users with server admin or role overrides will still be able to see the channels in the server. _If you're still having issues using m-mode please contact us via the discord support server. **Read this carefully first.**_

Looking to unlock your server? Have a look here:

{% page-ref page="server-unlock.md" %}



