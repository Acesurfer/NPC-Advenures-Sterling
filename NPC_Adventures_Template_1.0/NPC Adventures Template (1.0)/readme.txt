This guide is meant as a helpful tool to create your own NPC Adventure pack for the newest version of NPC Adventures!
Please note this is for 1.0 only. Prior versions, such as 0.17.5, run on different rules and are not supported by this.

Please note that both folders are necessary. If you put a content.json in the [NA] folder NPC Adventures will disallow loading your NPC Adventure pack.
Also, do not rename the "companions" folder in NA or the game will not recognize your companion.

The following is the suggested order of edits, based on folders.
1. NA manifest
2. NA companions
3. NA i18n (write your buff description line in here, after having decided on buffs in companions
4. CP Manifest
5. CP Content
6. CP Mail
7. CP Dialogue & Speech Bubbles
8. CP Forage, if your companion is a forager and you want custom forage values.
9. CP Locale folders, if you have any translations you'd like to include. Make sure to remove the period from in front of the translation's content.json when complete! (Translation content.json is in locale folder, do not move it)

Each document has instructions within them (even the manifests, although for obvious reasons those are kept to a minimum).

If you are confused, please head to the NPC Adventures website for 1.0 upgrades (next.npcadventures.dev).
Specifically, https://next.npcadventures.dev/docs/modding/upgrading and the resulting links on the sidebar should help.

For translations, it's essentially the same setup as the normal folders (just write it in Content Patcher format). Remove the period in the content.json in a relevant folder copied from the example "French" translation 
to make the relevant folder work, and just copy out the "fr" folder for how many translations you have. The locale folder is needed instead of i18n due to the inability to
variate dialogues with i18n (which is odd, but it's how it is).

(Ignore and/or remove the Swimsuits json unless for some reason Stardew's normal swimsuit function does not function when using NPC Adventures.)

