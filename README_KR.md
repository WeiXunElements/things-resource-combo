# things-resource-combo

## things-resource-combo. things-ajax 컴퍼넌트를 이용하여 resource data를 조회, 콤보박스의 형태로 출력하고 선택한 값을 input field에 표시하는 컴퍼넌트

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

## 서버에 저장되어 있는 Common 코드 정보를 조회하여 콤보로 표시하는 컴포넌트

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

## 다국어 설정을 위한 Locale Selector
```html
Example:

  <things-locale-combo
    id="locale-selector"
    storage-name="setting.locale"
    default-locale="{{defaultLocale}}"
    selected-locale="{{globals.locale}}">
  </things-locale-combo>
```

# things-storage-combo.
## things-ajax 컴퍼넌트를 이용하여 storage_infos의 data를 조회, 콤보박스의 형태로 출력하고 선택한 값을 input field에 표시하는 컴퍼넌트

Example:
```html
    <things-storage-combo
      name="storage"
      label="Storage">
    </things-storage-combo>
```

#	things-menu-combo
## things-ajax 컴퍼넌트를 이용하여 menu data를 조회, 콤보박스의 형태로 출력하고 선택한 값을 input field에 표시하는 컴퍼넌트

Example:
```html
		<things-menu-combo
			value="{{value}}">
		</things-menu-combo>
```

## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

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
