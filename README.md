# login

This is the login page used to authenticate your Twitch account with Chatterino.

The production version is deployed at https://chatterino.com/client_login

## Scopes

Below is a list of our scopes in the "human readable" format that Twitch provides, with an explanation for each scope.

- **Block users on your behalf**  
  From the `user_blocks_edit` scope, used to let you block users using the `/block` chat command or checking the "Block" checkbox in a users card.  
  _Deprecated_, will be replaced with the `user:manage:blocked_users` scope fully soon.
- **Manage your followed channels**  
  From the `user_follows_edit` scope, used to let you follow users using the `/follow` chat command or checking the "Follow" checkbox in a users card.  
  _Deprecated_, will be replaced with the `user:edit:follows` scope fully soon.
- **Update your channel's title, game, status, and other metadata**  
  From the `channel_editor` scope, used to let you use the `/raid` command to raid users on Twitch.
- **Cut VODs**  
  From the `channel_editor` scope, used to let you use the `/raid` command to raid users on Twitch.
- **Perform moderation actions in a channel**  
  From the `channel:moderate` scope, used to let you use the `/ban`, `/clear`, `/slow`, `/subscribers` etc moderator commands.
- **Send live Stream Chat and Rooms messages**  
  From the `chat:edit` scope, used to let you type in Twitch chats.
- **View your whisper messages**  
  From the `whispers:read` scope, used to let Chatterino display Twitch whispers you receive.
- **Send whisper messages**  
  From the `whispers:edit` scope, used to let you reply to whispers through Chatterino with the `/w` command.
- **Run commercials on a channel**  
  From the `channel_commercial` scope, used to let you use the `/commercial` command to run commercials on other users Twitch channels (that you have permission for).
- **Edit your follows**  
  From the `user:edit:follows` scope, used to let you follow users using the `/follow` chat command or checking the "Follow" checkbox in a users card.
- **Manage your channel's broadcast configuration, including updating channel configuration and managing stream markers and stream tags.**  
  From the `channel:manage:broadcast` scope, used to let you use the `/marker` command to create a Stream Marker, and for `/settitle` and `/setgame` to update the channels title and game.
- **Get a list of all users on your block list.**  
  From the `user:read:blocked_users` scope, used to let Chatterino fetch the list of users you have blocked with your Twitch account so it can list them to you in the "Ignored users" settings page.
- **Add and remove users from your block list.**  
  From the `user:manage:blocked_users` scope, used to let you block users using the `/block` chat command or checking the "Block" checkbox in a users card.
- **View the users you have blocked**  
  From the `user_blocks_read` scope, used to let Chatterino fetch the list of users you have blocked with your Twitch account so it can list them to you in the "Ignored users" settings page.  
  _Deprecated_, will be replaced with the `user:read:blocked_users` scope fully soon.
- **View Channel Points custom rewards and their redemptions on your channel**  
  From the `channel:read:redemptions` scope, used to properly render Channel Point redemptions as they appear in chat (fetch their display name and icon etc).
- **Run commercials on your channel**  
  From the `channel_commercial` scope, used to let you use the `/commercial` command to run commercials on your Twitch channel.
- **Create clips from a broadcast or video**  
  From the `clips:edit` scope, used to let you use the `/clip` command to create a Twitch clip.
- **View your paid subscriptions**  
  From the `user_subscriptions` scope, used to let Chatterino figure out which emotes your Twitch account is able to use (including Subscription emotes)
- **View live Stream Chat and Rooms messages**  
  From the `chat:read` scope, used to let you read Twitch chats.
