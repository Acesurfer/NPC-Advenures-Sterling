This guide is for upgrading NPC Adventures ONLY. If you're making a new one, refer to the other ZIP file included!
Please note that both folders are necessary. If you put a content.json in the [NA] folder NPC Adventures will disallow loading your NPC Adventure pack.
Also, do not rename the "companions" folder in NA or the game will not recognize your companion.

The following is the suggested order of creation.
1. CP Manifest
2. CP Content
3. CP Mail
4. CP Dialogue & Speech Bubbles
5. CP Forage, if your companion is a forager and you want custom forage values.
5. CP Locale folders, if you have any translations you'd like to include.
6. NA manifest
7. NA i18n
8. NA companions (this will require the most, as most of the prior files have been merged into this one. Still, it's fairly simple.)


Each document has instructions within them (even the manifests, although for obvious reasons those are kept to a minimum).

If you are confused, please head to the NPC Adventures website for 1.0 upgrades (next.npcadventures.dev).
Specifically, https://next.npcadventures.dev/docs/modding/upgrading and the resulting links on the sidebar should help.

For translations, it's essentially the same setup as the normal folders (just write it in Content Patcher format). Remove the period in the content.json in a relevant folder copied from the example "French" translation 
to make the relevant folder work, and just copy out the "fr" folder for how many translations you have.

Otherwise, simply go into each folder in the Locale folder and paste in the dialogues from the translations. Super simple!
