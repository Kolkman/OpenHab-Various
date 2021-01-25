### Howto

In OpenHab 3.0

##### Create the thing and needed items
 * Install the OpenHab Spotify Binding
 * For each user configure a Spotify Player Bridge as a Thing
 * In your Model page choose 'create Equipment from Thing' (for each user you have a thing, so you may need to do this more than once)
     * Select all defaults. Additonally thick 'Show Advanced' and and include 'Track Progres (ms)' and 'Track Duration (ms)' 
 
 
##### Install the widget
 * Go to the 'Developers Tools'
 * Select 'Widgets' press the '+' icon.
 * Delete all text in the edit window
 * Paste all the code from [Spotify-Widget.yaml](https://github.com/Kolkman/OpenHab-Various/blob/main/OH3%20Widgets/Spotify%20Widget/Spotify-Widget.yaml) into the edit window
 * Safe the lot: ctrl+s
 
 ##### Use the widget
 * in your pages editor you can select the widget from your Personal Widgets
 * in its properties you have to select the SpotifyPlayerBridge you created above. The widget will use that string to select all the channels it needs for operations. 


#### Acknowledgement

The [Sonos Interface](https://community.openhab.org/t/sonos-player-widget-for-oh3-mainui/108327) got me going.
