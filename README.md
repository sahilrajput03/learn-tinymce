# learn tinymce

- Getting generated Html form the modifications you made in tinymce editor:
  - or via menu: `View > Source Code`
  - via code:
    ```js
    tinyMCE.get('basic-example').getContent()
    ```
- Make it work with react: [Click here](https://www.tiny.cloud/docs/tinymce/6/react-cloud/)
- Article - How to set up the TinyMCE save plugin with EXPRESSJS - [Click here](https://www.tiny.cloud/blog/set-up-the-tinymce-save-plugin/)
- Saving in Docs: [Click here](https://www.tiny.cloud/docs/plugins/opensource/save/)
- **FYI:** There is another less common and newer tool as well: https://github.com/froala/wysiwyg-editor

## Feedback

Its not much worth:
- saving implementation is not there from the software itself.. as they are just providing the frontend html editor build only (no backend to sync with real files at all so its good for beginners only)
- multiple file support won't be even possible even if you try to get the generated output html and thus its not something to be used while building professional websites or anything
