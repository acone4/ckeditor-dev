@bender-tags: selection, 4.12.1, bug, 3161
@bender-ui: collapsed
@bender-ckeditor-plugins: wysiwygarea, toolbar, elementspath, sourcearea, list, undo, div

1. Double click on word `Bar`.

1. Press `insert` button below the editor.

  ## Expected

  No red boarder is visible.

  ## Unexpected

  Red border is visible.

1. Press `reset` button.

1. Start selection word `Foo` by mouse from the left.

1. Release mouse over the bullet of sub list.

1. Press `insert` button.

## Expected

No red boarder is visible.

## Unexpected

Red border is visible.