# Kitefold 4.3 release notes

Released June 23, 2026

Release 4.3 is mostly about Image Anchor. One experience can now respond to more than one picture. Below you'll find what's new, what we improved, and what we fixed.

## New

**Multiple target images in Image Anchor.** Since release 4.3 (June 23, 2026), a single Image Anchor experience can use up to 5 target images. Before, each experience was tied to one image, so a catalog, a set of packaging variants or a row of posters meant building a separate experience for every picture. Now you add the images to one experience, and each one can trigger its own content.

How it works in the editor:

1. Open your Image Anchor experience and go to the Targets panel.

2. Add images one at a time, up to the limit of 5.

3. Select a target to place its content on the 3D viewport. Each target keeps its own layout, so the content for one image never moves when you edit another.

4. Preview with the images printed or on a second screen, then publish.

Tip: choose target images that look clearly different from one another. Images that share the same layout, colors and large areas of flat color are harder to tell apart, and tracking quality drops.

## Improved

- **Target quality hints.** When you upload an image, the editor now explains why it may track poorly, such as low contrast, repeating patterns or large blank areas, and suggests a fix.

- **Target list.** Targets show a thumbnail and a name you can edit, so it's easier to tell them apart in a longer list.

- **Switching between targets.** When a visitor moves the camera from one target image to another, the handoff is smoother, and the previous content stops rendering sooner.

- **Duplicate and reorder.** You can duplicate a target together with its content and drag targets into a new order.

- **Analytics.** Image Anchor reports can be filtered by target, so you can see which image gets scanned most.

## Fixed

- Fixed a case where a target image with a transparent background was rejected without a clear message. The editor now accepts it or tells you what to change.

- Fixed an issue where undo in the Canvas editor could restore a deleted target without its content.

- Fixed a preview problem where content stayed visible for a moment after the target image left the camera view.

- Fixed a layout glitch in the Targets panel on narrow browser windows.

- Fixed an inconsistent label in the publish dialog that mixed up "target" and "marker."

## Good to know

- Experiences you already built with a single target image keep working exactly as before. The new limit only applies when you add more images.

- Legacy Marker tracking is still deprecated. If you haven't moved those experiences to Image Anchor yet, 4.3 is a good moment to start, since multiple targets cover many cases that used to need several markers.

- Facecast, generally available since release 4.2, is unchanged in this release.

Questions about the new Targets panel? Write to Kitefold Care and a person will get back to you.

Maya Lindqvist, Founder and CEO