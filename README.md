# jQuery - Add/Delete Tags with jQuery Input Plugin #****

jQuery plugin converts a simple text input into a tag list with remove tag option.

This plugin creates a input in your form that will contains a comma-separated list of tags.

Simply call the tagsInput function on any field that should be treated as a list of tags.

$('#tags_tg').tagsInput();

**To add tags -** Call the addTag() function.
$('#tags_tg').addTag('foo');

**To remove tags -** Call the removeTag() function.
$('#tags_tg').removeTag('bar');

**To import a list of tags -** Call the importTags() function.
$('#tags_tg').importTags('foo,bar,baz');

**To reset the tag list -** Call the importTags() function.
$('#tags_tg').importTags('');

By default, if the cursor is immediately after a tag and you are hitting backspace will 
delete that tag.