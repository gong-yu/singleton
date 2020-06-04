# How to contribute to Singleton documentation?

Follow [Singleton contributing guideline](https://github.com/vmware/singleton/blob/master/CONTRIBUTING.md) to fork and clone Singleton project source code.

Switch to website branch.

```
git checkout website
```

Download the theme files for the website.

```
git submodule init
git submodule update
```

##### Add a new document

```
hugo new [document-name].md //e.g. hugo new docs/get-started/overview.md
```

##### Modify the content of existing documents

Please directly modify the contents in .md files under /content if needed using any markdown file editor.

After your modification is done, push your change to your fork project. Then go to GitHub and create PR to the upstream website branch. Once your PR is merged, the change will be automatcially deployed to the website https://vmware.github.io/singleton/docs/.

