# $arrayClear

empty the array

## Usage

```bash
$arrayClear[array name (optional)]
```

### Example:
<discord-messages>
          <discord-message :bot="false" role-color="#ffcc9a" author="Member">
        !!exec $textSplit[Hello World; ]<br>Before=$arrayJoin[, ]<br>$arrayClear<br>After=$arrayJoin[, ]<br><br>
          </discord-message>
          <discord-message :bot="true" role-color="#0099ff" author="Custom Command" avatar="https://media.discordapp.net/avatars/725721249652670555/781224f90c3b841ba5b40678e032f74a.webp">
        Before=Hello, World<br>After=
        </discord-message>
</discord-messages>