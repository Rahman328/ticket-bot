# 🤖 Commands

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
Bir ticket kanalında kullanarak üye herhangi bir mesaj yazmaya devam ederse bot sizi etiketler `!alert`.

### `!loglink`
Bir ticket kanalında kullanarak ticket log linkini alırsınız.

### `!loglink -s`
Bir ticket kanalında kullanarak ticket log linkini alırsınız(moderatör yorumlarını göstermez).

### `!loglink -v`
Get a link to the open Modmail thread's log, showing extra details about channel and message IDs between the bot and the user.
This is mainly useful when reporting messages to Discord's Trust & Safety team.

### `!id`
Bir ticket kanalında kullanarak ticketi açan kişinin idsini alırsınız.

## Anywhere on the inbox server
These commands can be used anywhere on the inbox server, even outside Modmail threads.

### `!newthread <userID>`
IDsi girilen üyeye özel yeni ticket konusu açar.

**Example:** `!newthread 106391128718245888`

### `!logs <userID>`
IDsi girilen kullanıcının loglarını gösterir.

**Example:** `!logs 106391128718245888`

### `!block <userID>`
Kullanıcıyı sistemden blocklar.

**Example:** `!block 106391128718245888`

### `!block <userID> <time>`
Belirtilen süre boyunca kullanıcıyı sistemden yasaklar.

**Example:** `!block 106391128718245888 7d`

### `!unblock <userID>`
Üyenin blockunu kaldırır ve tekrar sistmei kullanabilmesini sağlar

**Example:** `!unblock 106391128718245888`

### `!is_blocked <userID>`
üyenin blocklu olup olmadığını kontrol eder

**Example:** `!is_blocked 106391128718245888`

### `!version`
bot sürümünü gösterir

## Snippets (canned messages)
See the [📋 Snippets](snippets.md) page for more information!  `bu kısmı çevirmedim fakat kısaca anlatmak gerekirse , hızlı cevap vermenizi sağlayan içerikler yaratabiliyorsunuz snippets.md klasörüne giderek görebilirsiniz detaylı bir şekilde.`
