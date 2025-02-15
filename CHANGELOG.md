# Change Log

## 2.1.4

_Requires WordPress 5.0_
_Tested up to WordPress 5.9_

### Bug Fixes

- Stop using WP i18n Grunt task and @wordpress/babel-plugin-makepot to generate pot/json files.
- Use `wp.date.isInTheFuture()` to check whether a post type is scheduled or not.
- Make sure the link to browse revisions is added into the Classic Editor.

### Props

@pdobrescu

---

## 2.1.3

_Requires WordPress 5.0_
_Tested up to WordPress 5.8.0_

### Bug Fixes

- For WordPress >= 5.8, stop using the deprecated filter `block_editor_preload_paths` in favor of `block_editor_rest_api_preload_paths`.

### Props

@rodrigo-arias

---

## 2.1.2

_Requires WordPress 5.0_
_Tested up to WordPress 5.7.0_

### Bug Fixes

- Makes the WP_Statuses_Core_Status::_builtin property public, so it is accessible by `is_post_status_viewable()`.

### Props

@andronocean

---

## 2.1.1

_Requires WordPress 5.0_
_Tested up to WordPress 5.5.1_

### Bug Fixes

- Make sure the plugin can be used with the Classic Editor plugin when WP is >= 5.5 or WP is < 5.5.

### Props

@andrefredette

---

## 2.1.0

_Requires WordPress 5.0_
_Tested up to WordPress 5.4.1_

### Bug Fixes

- Make sure trashing a post from the Block Editor is redirecting the user on the edit screen of the post type.
- Make sure Post types `template` and `template_lock` properties are taken in account and that the blocks set in the template are inserted into the Block Editor.

### Props

@leorospo

---

## 2.0.1

_Requires WordPress 5.0_

### Features

- Italian translation.

### Props

@leorospo

---

## 2.0.0

_Requires WordPress 5.0_

### Features

- WP Statuses is now ready to manage your custom statuses within the WordPress Block Editor 🙌

### Props

@rowatt

---

## 1.2.5

_Requires WordPress 4.7_

### Bug Fixes

- Fix PHP warnings for scheduled posts.

### Props

@rowatt, @lajala

---

## 1.2.4

_Requires WordPress 4.7_

### Features

- Adds a Composer config file.

### Props

@AdamQuadmon

---

## 1.2.3

_Requires WordPress 4.7_

### Bug fixes

- Adds the missing CHANGELOG to repository.

### Features

- Spanish translation.
- Use the Git Archive npm module instead of the compress one.

### Props

@delmicio

---

## 1.2.2

_Requires WordPress 4.7_

### Bug fixes

- Adds the missing GNU/GPL2 license to repository.

### Features

- Adds a `Github Plugin URI header tag for easier upgrades using the Github Updater plugin or the Entrepôt plugin.
- Adds a plugin icon to be used by the Entrepôt plugin.

---

## 1.2.1

_Requires WordPress 4.7_

### Bug fixes

- Avoid confusions between taxonomy terms and statuses for the custom example.
- Make sure the Attachment post type is not concerned by custom statuses.

### Features

- German translation.
- Introduce a filter to remove the custom post statuses support from custom post types.

### Props

@mediastuttgart @toshotosho

---

## 1.2.0

_Requires WordPress 4.7_

### Bug fixes

- Avoid confusions between taxonomy terms and statuses for the custom example.

### Features

- Introduce more customizable labels for the Metabox strings.
- Make the Publishing Metabox JavaSscript less dependant of WordPress & ready for custom labels.

### Props

@GaryJones

---

## 1.1.0

_Requires WordPress 4.7_

### Bug fixes

- Make sure custom statuses cannot be sticked to front.

### Features

- Add a property to support custom statuses integration within Press This.

---

## 1.0.0

_Requires WordPress 4.7_

### Features

- Improve the WordPress Post statuses API by allowing custom Post statuses.
