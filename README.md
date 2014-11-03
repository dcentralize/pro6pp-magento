pro6pp-magento
==============

The repository of the \*.diff files that are extracted after integrating
the Pro6PP service into magento.

## How to install

### Get the diff files from Github with either of the two available ways.

* `git clone`
* Download the repository as a .zip file
* Extract or open the pro6pp-magento folder
* Copy or open the folder with the name equal to the Magento (Community Edition) version you have installed.

### Apply the patches to your Magento installation

You will have to manually apply
the patches using the provided `.diff` files.

```shell
patch path/to/original/file path/to/pro6pp/diff/file
```

If the above command fails during execution, you can revert the patch

```shell
patch -R path/to/original/file path/to/pro6pp/diff/file
```

And open the diff files in order to do the changes via the text editor of your preference.
