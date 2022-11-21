## Flashcard with images

You can define flashcards with images using relative links. It doesn't matter if you want to locate all your images at the top level of the project, or in folders you define.

Here is how to reach an image in the root directory. By way of example, the `md2apkg` logo located in the root directory of this project (not inside `/Deck/`, just `/md2apkglogo.png`)

![image relative linked from top level](../../../md2apkglogo.png)

%

And here's an example with the same image but located in a folder adjacent to where the flashcard you're reading is defined. Namely, this flashcard is located in `/Deck/tagA/tag_C/imageinside.md`, while the image in this next example is located in `/Deck/tagA/tag_C/images/md2apkglogo.png`.

![image relative linked from an adjacent folder](./images/md2apkglogo.png)

## Things to think about when including images in your flashcards

How you decide to structure this just depends on what makes the most sense for your project, or whatever you find most convenient. You might keep evey image in a folder at the top level (feel free to define an `/images/` folder adjacent to `Deck`, for instance), if you want to keep all your image assets in one location. This would potentially make the most sense if you want to use the same image in multiple flashcards (especially if those flashcards are scattered across `.md` files in various subdirectories).

%

It might make more sense for you to keep images next to the `.md` files that reference them, if you don't intend to use the image in more than one flashcard. I didn't need to put the image in a `./images/` folder in this example. If you prefer, you can keep images right next to your Markdown files without creating a dedicated folder to tuck images inside. This is
