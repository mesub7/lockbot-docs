# Mute

Has somebody passed the warning threshold for mutes? Have they been spamming a bit too much? The mute command ensures that they won't be able to talk in any channels\*.

\*Subject to permissions being set up correctly.

{% hint style="success" %}
**Format: \[prefix\]mute @user \[time in minutes \(no units\)\]**

**User permissions required: Lock Bot added mods/admins OR Kick members**

**Bot permissions required: Manage roles, Manage members, Manage channels** – _It's advised that lock bot should have full server admin to carry out functions correctly._
{% endhint %}

Once the command has been run, the "Muted" role will be applied to the user. A confirmation message will be posted that the user has been muted for a certain amount of minutes.

![The confirmation of a mute.](../.gitbook/assets/image%20%283%29.png)

{% hint style="info" %}
## Mute issues

If there are issues \(the user can still talk\) then please read the following information before going to support:

If the user has got the Muted role but still can talk means then there's issue with your channel permissions.

Go to `Channel Settings` -&gt; `Permissions`

If that's public channel that can be accessed by anyone:

* Set ![:GrayTick:](https://cdn.discordapp.com/emojis/452773421294813185.png?v=1) `Send Messages` for all roles except Muted.
* Set ![:RedTick~1:](https://cdn.discordapp.com/emojis/375575883097833483.png?v=1) `Send Messages` for the Muted role.

If that's secret channel that requires a specific role to access it:

* Set ![:GrayTick:](https://cdn.discordapp.com/emojis/452773421294813185.png?v=1) `Send Messages` ![:GreenTick~2:](https://cdn.discordapp.com/emojis/375576212568801280.png?v=1) `Read Messages` for the specific role.
* Set ![:RedTick~1:](https://cdn.discordapp.com/emojis/375575883097833483.png?v=1) `Send Messages` ![:GrayTick:](https://cdn.discordapp.com/emojis/452773421294813185.png?v=1) `Read Messages` for the Muted role.
* Set ![:GrayTick:](https://cdn.discordapp.com/emojis/452773421294813185.png?v=1) `Send Messages` ![:RedTick~1:](https://cdn.discordapp.com/emojis/375575883097833483.png?v=1) `Read Messages` for  the`@​everyone` role.

If you are still having issues then visit the discord server.
{% endhint %}

