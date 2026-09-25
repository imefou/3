Each project is one .json file in this folder, e.g. my-project.json:

{
  "title": "My Cool Project",
  "description": "A short description of what this is.",
  "category": "video",
  "images": [
    "img/projects/my-project-1.jpg",
    "img/projects/my-project-2.jpg"
  ]
}

"category" must be either "video" (shows under the Video Editing tab)
or "minecraft" (shows under the Minecraft tab).

Drop the .json file here and the matching images in img/projects/,
push to GitHub, and the card appears on the Projects page automatically,
under the right tab. No other files need to be edited.
