# things-resource-combo

## 이는 things-ajax 컴포넌트를 이용하여 resource data를 조회, 콤보박스의 형태로 출력하고 선택한 값을 input field에 표시하는 컴포넌트이다.

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

## 이는 서버에 저장되어 있는 Common 코드 정보를 조회하여 콤보로 표시하는 컴포넌트이다.

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

## 이는 다국어 설정을 위한 Locale Selector이다.
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

## 이는 things-ajax 컴포넌트를 이용하여 storage_infos의 data를 조회, 콤보박스의 형태로 출력하고 선택한 값을 input field에 표시하는 컴포넌트이다.

Example:
```html
    <things-storage-combo
      name="storage"
      label="Storage">
    </things-storage-combo>
```

# things-menu-combo

## 이는 things-ajax 컴포넌트를 이용하여 menu data를 조회, 콤보박스의 형태로 출력하고 선택한 값을 input field에 표시하는 컴포넌트이다.

Example:
```html
		<things-menu-combo
			value="{{value}}">
		</things-menu-combo>
```

## Dependencies

element의 종속성은 [Bower](http://bower.io/)를 통해 관리되며, 아래의 방법을 통해 설치할 수 있다.

    npm install -g bower

다음, element의 종속성을 다운로드한다.

    bower install


## Playing With Your Element

element를 독립적으로 처리하려면 [Polyserve](https://github.com/PolymerLabs/polyserve)를 사용하여 element의 bower 의존성을 유지하도록 하며, 이는 아래의 방법을 통해 설치할 수 있다.

    npm install -g polyserve

그리고, 아래의 방법을 통해 실행할 수 있다.

    polyserve

element를 실행한 경우, `things-resource-combo`가 디렉토리 이름으로 포함되어 있는 `http://localhost:8080/components/things-resource-combo/`를 통해 이를 미리 확인할 수 있다. 