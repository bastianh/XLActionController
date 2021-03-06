# Change Log

All notable changes to this project will be documented in this file.

### master branch

### [2.1.0](https://github.com/xmartlabs/XLActionController/releases/tag/2.1.0)

* **Breaking change**: `actionTitleLabelConstraintToContainer` and `actionTitleLabelConstraintToImageView` was removed from `ActionCell` class. You must delete these outlets from your xib files, [PR #23](https://github.com/xmartlabs/XLActionController/pull/23). 
* **Breaking change**: actions' handlers are now executed after the action controller was completely dismissed, [PR #22](https://github.com/xmartlabs/XLActionController/pull/22).
* Fixed duplicated execution of actions, [PR #22](https://github.com/xmartlabs/XLActionController/pull/22).

### [2.0.0](https://github.com/xmartlabs/XLActionController/releases/tag/2.0.0)

* Bug fixes and stability improvements.
* added support for Xcode 7.3 and swift 2.2.

### [1.0.0](https://github.com/xmartlabs/XLActionController/releases/tag/1.0.0)
Released on 2015-12-11. This is the initial version.
