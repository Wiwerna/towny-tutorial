# towny-tutorial
A towny tutorial for S2.

## Town
/town (/t) - **Shows a player their town's town screen.**

/town (/t) ? - **Shows /town commands available.**

/town (/t) {town} - **Shows a player another town's town screen.**

/town (/t) here - **Shows you the town screen of the town in which you stand.**

/town (/t) leave - **Leaves a town.**

/town (/t) list - **Lists towns.**

/town (/t) online - **Shows players in your town which are online.**
### /town (/t) new
/town (/t) new {townname} - **Creates new town.**

/town (/t) new {townname} {mayor} - **Admin command to create town.**

/town (/t) add {resident} .. {resident} - **Mayor command to add residents to your town.**

/town (/t) kick {resident} .. {resident} - **Mayor command to remove residents from your town.**

/town (/t) spawn - **Teleports you to your town's spawn.**

/town (/t) spawn {town} - **Teleports you to another town's spawn.**

/town (/t) claim - **Mayor command to claim the townblock in which you stand for your town.**
### /town (/t) claim
/town (/t) claim outpost - **Claims an outpost for your town.**

/town (/t) claim {# (radius around current position)} - **Claims an area of townblocks around you for your town.**

/town (/t) claim auto - **Claims as many townblocks around you as is possible given money in townbank and available townblocks.**

/town (/t) unclaim - **Mayor command to unclaim the townblock in which you stand.**
### /town (/t) unclaim
/town (/t) unclaim all - **Mayor command to unclaim all townblocks.**

/town (/t) unclaim {# (radius around current position)} - **Command to unclaim an area of townblocks around you.**

/town (/t) withdraw {$} - **Removes money from town bank.**

/town (/t) deposit {$} - **Adds money from player to the town bank.**
### /town (/t) buy
/town (/t) buy bonus {amount} - **Buys available bonus townblocks.**

/town (/t) delete {town name} - **Admin/Mayor command to delete a town from towny's data folder's files.**
### /town (/t) outpost
/town (/t) outpost {# (where # equals the corresponding outpost's number)} - **Teleports to an outpost.**

/town (/t) ranklist - **Displays residents and their ranks.**

/town (/t) rank {add|remove} {playername} {rankname} - **Grants or removes a rank to a resident of the town.**

/town (/t) reslist - **Displays a full list of residents in the town.**
***/town (/t) set***
/town (/t) set board {message} - **Sets message seen by residents upon logging in.**

/town (/t) set mayor {resident} - **Mayor command to give mayor status to another resident.**

/town (/t) set homeblock - **Sets the homeblock and spawn of your town.**

/town (/t) set spawn - **Sets the town spawn, must be done inside the homeblock.**

/town (/t) set name {name} - **Change your town's name.**

/town (/t) set outpost - **Sets a townblock as an outpost.**
### /town (/t) set perm
/town (/t) set perm {on/off} - **Edits the perm line on the town screen.**

/town (/t) set perm {resident/ally/outsider} {on/off}

/town (/t) set perm {build/destroy/switch/itemuse} {on/off}

/town (/t) set perm {resident/ally/outsider} {build/destroy/switch/itemuse} {on/off}

/town (/t) set perm reset - **This takes the perm line seen in the /town screen and applies it to all plots owned by the town.**

/town (/t) set tag {upto4character} - **Sets the town's tag, which is sometimes used on that chat line.**

/town (/t) set clear - **Clears the tag set for the town.**

/town (/t) set taxes {$} - **Sets taxes collected from each resident daily. Also sets percentage if taxpercent is toggled on.**

/town (/t) set plottax {$} - **Set taxes collected from each resident daily, per plot that they own.**

/town (/t) set plotprice {$} - **Sets default cost of plot for the town.**

/town (/t) set shopprice {$} - **Sets default cost of a shopplot for the town.**

/town (/t) set shoptax {$} - **Set taxes collected from each resident daily, per shopplot that they own.**

/town (/t) set embassyprice {$} - **Sets default cost of a embassy plot for the town.**

/town (/t) set embassytax {$} - **Set taxes collected from each resident daily, per embassy plot that they own.**
### /town (/t) toggle
/town (/t) toggle explosion - **Turn on/off explosions in town.**

/town (/t) toggle fire - **Turn on/off firespread in town.**

/town (/t) toggle mobs - **Turn on/off hostile mobspawning in town.**

/town (/t) toggle public - **Turn on/off public /town spawning and the co-ordinates of the town's homeblock in the /town screen.**

/town (/t) toggle pvp - **Turn on/off pvp in town.**

/town (/t) toggle taxpercent - **Turn on/off taxing by percent/flatrate.**

/town (/t) toggle open - **Turn on/off public joining to your town.**

/town (/t) join {townname} - **Command to join a town that doesn't require invites.**
## /nation
/nation (/n) - **Shows a player their nation's nation screen.**

/nation (/n) ? - **Shows /nation commands.**

/nation (/n) list - **Lists nations.**

/nation (/n) online - **Shows players in your nation which are online.**

/nation (/n) {nation} - **Shows a player the /nation screen of another nation.**

/nation (/n) leave - **Mayor command to leave the nation they are a part of.**

/nation (/n) withdraw {$} - **King command to remove money from the nation bank.**

/nation (/n) deposit {$} - **King command to add money to the nation bank.**
### /nation (/n) new
/nation (/n) new {nationname} - **Mayor command to create a nation.**

/nation (/n) new {nationname} {capitaltown} - **Admin command to create a new nation, set capitol.**

/nation (/n) rank - **Command to set assistant/custom ranks in the nation.**

/nation (/n) add {town} .. {town} - **Invites/Adds a town to your nation.**

/nation (/n) kick {town} .. {town} - **Removes a town from your nation.**

/nation (/n) delete {nation} - **Deletes your nation.**
### /nation (/n) ally
/nation (/n) ally add {nation} .. {nation} - **Add a nation to your nation's ally list.**

/nation (/n) ally remove {nation} .. {nation} - **Removes a nation from your nation's ally list.**
### /nation (/n) enemy
/nation (/n) enemy add {nation} .. {nation} - **Add a nation to your nation's enemy list.**

/nation (/n) enemy remove {nation} .. {nation} - **Removes a nation from your nation's enemy list.**

/nation (/n) rank {add|remove} {playername} {rankname} - **Grants or removes a rank to a resident of the nation.**
### /nation (/n) set
/nation (/n) set king {resident} - **King command to change the king of the nation.**

/nation (/n) set captial {town} - **Sets the capitol and king of the nation.**

/nation (/n) set taxes {$} - **Sets nationtax applied to the towns within the nation.**

/nation (/n) set name {name} - **Sets the nation's name.**

/nation (/n) set title {name} {titlegoeshere} - **King command to add a Title to a member of the nation.**

/nation (/n) set surname {name} {surnamegoeshere} - **King command to add a Suffix to a member of the nation.**

/nation (/n) set tag {upto4character} - **Sets the nation's tag, which is sometimes used on that chat line.**

/nation (/n) set clear - **Clears the tag set for the nation.**
### /nation (/n) toggle
/nation (/n) toggle neutral - **Sets whether your nation will pay daily to be neutral during towny war.**
## /resident
/resident - **Shows a player their resident screen.

/resident ? - **Shows /res commands available.

/resident {resident} - **Shows a player another player's resident screen.**
### /resident friend
/resident friend add {resident} .. {resident} - **Resident adds online player to their friends list.**

/resident friend add+ {resident} .. {resident} - **Resident adds offline player to their friends list.**

/resident friend remove {resident} .. {resident} - **Resident removes online player from their friends list.**

/resident friend remove+ {resident} .. {resident} - **Resident removes offline player from their friends list.**

/resident friend clearlist - **Removes all friends from a resident's friend list.**

/resident list - **Lists residents in towny's data folder.**

/resident spawn - **If deny_bed_use: true in the config.yml and player has a current bed spawn, command will teleport player to their bed.**
### /resident toggle
/resident toggle map - **Turns on map which refreshes when moving across plot borders.**

/resident toggle townclaim - **Turns on mode where /town claim is automatically used when moving across plot borders.**

/resident toggle plotborder - **Turns on smokey plot-border view. Border shows when players cross to different townblocks.**

/resident toggle spy - **Admins can turn on chat-channel spying.**

/resident toggle reset - **This turns off all modes that are active.**
### /resident set
/resident set perm

/resident set {on/off} - **Edits the perm line on the resident screen. See here for details.**

/resident set {friend/ally/outsider} {on/off}

/resident set {build/destroy/switch/itemuse} {on/off}

/resident set {friend/ally/outsider} {build/destroy/switch/itemuse} {on/off}

/resident set reset - **This takes the perm line seen in the /resident screen and applies it to all plots personally owned by the player typing it.**

/resident tax - **Shows taxes a player pays.**
## /towny
/towny - **Shows basic towny commands.**

/towny ? - **Shows more towny commands.**

/towny map - **Shows the towny map.**

/towny prices - **Shows taxes/costs associated with running a town.**

/towny time - **Shows time until next new-day (tax/upkeep collection.)**
### /towny top
/towny top residents {all/town/nation} - **Shows top residents.**

/towny top land {all/resident/town} - **Shows top land owners.**

/towny spy - **Admin command to spy on all chat channels.**

/towny tree - **Shows lots of stuff.**

/towny universe - **Shows full towny stats, resident/town/nation/world counts as well as townblocks claimed.*"

/towny v - **Shows towny version.**
### /towny war
/towny war stats

/towny war scores
