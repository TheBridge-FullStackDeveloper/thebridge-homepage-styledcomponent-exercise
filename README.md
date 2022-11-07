# The bridge styled-component

In this task you'll replicate the bridge's home page and styling it with [styled-component](https://styled-components.com/docs) 💅

These is the section you'll replicate.

You can use your preferred react environment. ([CRA](https://create-react-app.dev/), [vite](https://vitejs.dev/), [codesandbox](https://codesandbox.io/), ...)

## 1. Install styled-component library

```sh
npm i styled-component
```

## 2. Component to be created:

- `Navbar` - Yellow rectangle

```css
 {
  background-color: #22172b;
  color: white;
  height: 60px;
}
```

- `Button` - Purple rectangle

```css
 {
  background-color: #e22a22;
  color: white;
  height: 38px;
}
```

- `SmallCard` - Red rectangle

```css
 {
  background-color: #e22a22;
  color: black;
  border-right: 5px solid #f7404c;
  border-bottom: 5px solid #f7404c;
  margin-right: 10px;
  margin-bottom: 20px;
  margin-left: 10px;
  padding: 20px;
}
```

- `BigCard` - Card rectangle

```css
 {
  display: flex;
  padding: 40px;
  flex-direction: column;
  justify-content: space-between;
}
```

![the-bridge](./styled-component.png)

## 3. Bonus 🏆

Develop `BigCard`'s animation carousels, when a user click on right arrow cards should be moved on the left, if left arrow is clicked cards should move on right side.

![image](https://user-images.githubusercontent.com/33903092/200269351-797e3344-ee30-4986-8aaf-41901b2f9570.png)
