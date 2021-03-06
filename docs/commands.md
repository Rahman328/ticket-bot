# ???? Commands

## Table of contents
* [Inside a Modmail thread](#inside-a-modmail-thread)
* [Anywhere on the inbox server](#anywhere-on-the-inbox-server)
* [Snippets (canned messages)](#snippets-canned-messages)

## Inside a Modmail thread
These commands can only be used inside a Modmail thread's channel on the inbox server.

### `!reply <text>` / `!r <text>`
Send a reply to the user.

**Example:** `!r How can I help you?`

To reply automatically without using `!reply`, [enable `alwaysReply` in bot settings](configuration.md).

### `!anonreply <text>` / `!ar <text>`
Send an anonymous reply to the user. Anonymous replies only show the moderator's role in the reply.

**Example:** `!ar Please only use Modmail for serious messages`

### `!close`
Close the Modmail thread.

### `!close <time>`
Close the Modmail thread after a timer. Sending a message to the user or receiving a message from the user will cancel scheduled closing.

**Example:** `!close 15m`

### `!close cancel`
Cancel a timed close.

### `!logs`
List previous Modmail logs with the user.

### `!block`
Block the user from using Modmail.

### `!block <time>`
Block the user from using Modmail for a specified time.

**Example:** `!block 7d`

### `!unblock`
Unblock the user, allowing them to use Modmail again.

### `!move <category>`
Move the Modmail thread to a different category.
Requires `allowMove` to be enabled in the bot's settings.

### `!suspend`
Suspend the thread.
The thread will act as closed and will not receive any messages until unsuspended via `!unsuspend`.

### `!unsuspend`
Unsuspend the thread. See `!suspend` above.

### `!alert`
Pings you when the thread gets a new reply.

### `!alert cancel`
Bir ticket kanal覺nda kullanarak 羹ye herhangi bir mesaj yazmaya devam ederse bot sizi etiketler `!alert`.

### `!loglink`
Bir ticket kanal覺nda kullanarak ticket log linkini al覺rs覺n覺z.

### `!loglink -s`
Bir ticket kanal覺nda kullanarak ticket log linkini al覺rs覺n覺z(moderat繹r yorumlar覺n覺 g繹stermez).

### `!loglink -v`
Get a link to the open Modmail thread's log, showing extra details about channel and message IDs between the bot and the user.
This is mainly useful when reporting messages to Discord's Trust & Safety team.

### `!id`
Bir ticket kanal覺nda kullanarak ticketi a癟an ki??inin idsini al覺rs覺n覺z.

## Anywhere on the inbox server
These commands can be used anywhere on the inbox server, even outside Modmail threads.

### `!newthread <userID>`
IDsi girilen 羹yeye 繹zel yeni ticket konusu a癟ar.

**Example:** `!newthread 106391128718245888`

### `!logs <userID>`
IDsi girilen kullan覺c覺n覺n loglar覺n覺 g繹sterir.

**Example:** `!logs 106391128718245888`

### `!block <userID>`
Kullan覺c覺y覺 sistemden blocklar.

**Example:** `!block 106391128718245888`

### `!block <userID> <time>`
Belirtilen s羹re boyunca kullan覺c覺y覺 sistemden yasaklar.

**Example:** `!block 106391128718245888 7d`

### `!unblock <userID>`
??yenin blockunu kald覺r覺r ve tekrar sistmei kullanabilmesini sa??lar

**Example:** `!unblock 106391128718245888`

### `!is_blocked <userID>`
羹yenin blocklu olup olmad覺??覺n覺 kontrol eder

**Example:** `!is_blocked 106391128718245888`

### `!version`
bot s羹r羹m羹n羹 g繹sterir

## Snippets (canned messages)
See the [???? Snippets](snippets.md) page for more information!  `bu k覺sm覺 癟evirmedim fakat k覺saca anlatmak gerekirse , h覺zl覺 cevap vermenizi sa??layan i癟erikler yaratabiliyorsunuz snippets.md klas繹r羹ne giderek g繹rebilirsiniz detayl覺 bir ??ekilde.`
