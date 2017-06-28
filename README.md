# things-resource-combo

## This is a component that displays the resource data using the things-ajax component, prints it in the form of a combo box, and displays the selected value in the input field.

Example:

```html
    <things-resource-combo
      name="user"
      label="Storage"
      resource-url="users"
      label-path="name"
      value-path="login">
    </things-resource-combo>
```

# things-code-combo

## This is a component that checks common code information stored in the server and displays it in combo.

Example:
```html
    <things-code-combo
      id="code-selector"
      label="Language"
      value="en-US"
      code-name="LOCALE"
      label-path="description"
      value-path="name">
    </things-code-combo>
```

# things-locale-combo

## This is a Locale Selector for multilingual configuration.
```html
Example:

  <things-locale-combo
    id="locale-selector"
    storage-name="setting.locale"
    default-locale="{{defaultLocale}}"
    selected-locale="{{globals.locale}}">
  </things-locale-combo>
```

# things-storage-combo

## This is a component that checks the data of storage_infos using the things-ajax component, prints it as a combo box, and displays the selected value in the input field.

Example:
```html
    <things-storage-combo
      name="storage"
      label="Storage">
    </things-storage-combo>
```

#	things-menu-combo

## This is a component that checks the menu data using the things-ajax component, prints it as a combo box, and displays the selected value in the input field.

Example:
```html
		<things-menu-combo
			value="{{value}}">
		</things-menu-combo>
```

## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install


## Playing With Your Element

If you wish to work on your element in isolation, we recommend that you use
[Polyserve](https://github.com/PolymerLabs/polyserve) to keep your element's
bower dependencies in line. You can install it via:

    npm install -g polyserve

And you can run it via:

    polyserve

Once running, you can preview your element at
`http://localhost:8080/components/things-resource-combo/`, where `things-resource-combo` is the name of the directory containing it.
