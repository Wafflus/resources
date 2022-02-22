# Genshin Impact Movement Resources

These are the necessary resources for my [Genshin Impact Movement System Tutorial Series](https://www.youtube.com/playlist?list=PL0yxB6cCkoWKuPoh_9dSvdItQENVx7YTW) if you don't feel like watching the Setup Videos.

# How do I use these?

Start by creating your 3D Project the way you want.

Then, override your existing `Assets` folder with the `Assets` folder I provide here.

When that's done, open up your Unity Project folder and navigate to the `Packages` folder *(it should be in the same place as your `Assets` folder)*.

Open up the `manifest.json` file and add the `dependencies` I've left in the `manifest.json` file I provide to the `dependencies` area.

Do the same for the `package-lock.json`.

Make sure you add a `,` to separate the dependencies if you place them above other dependencies.

Then, navigate to the `ProjectSettings` folder and do the same as above for the `EditorSettings.asset` and the `ProjectSettings.asset`, but instead of adding the setting, update its value to be the same as the one I provide *(as it should already exist in your Project)*.

Add the provided `ProjectSettings` `Packages` folder to your `ProjectSettings` folder.

Your Unity should then reload or restart and your Project should be all set up.

Unity will likely ask you if you want to disable the `Old Input System` as we use the `New Input System`, feel free to press `Yes`, or `No` if you want to keep the `Old Input System`.

If you chose `No`, update the `activeInputHandler` setting in the `ProjectSetting.asset` file to `2`.
