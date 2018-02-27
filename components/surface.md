# Surface
Container for all other ART components.

```js
render(){
  return (
    <Surface>
      { all other components }
    </Surface>
  )
}
```

Note that the `<Surface/>` element has default background color. You can remove it by using `backgroundColor: 'transparent'` in the node's `style` prop. 

#### Props

- [View props...](https://facebook.github.io/react-native/docs/view.html#props)
- [`width`](#width)
- [`height`](#height)
- [`visible`](#visible)

## Reference

### Props

<a name="width" />
#### `width`
The width of the target surface

| Type   | Required |
|:------:|:--------:|
| number | No       |

<a name="height" />
#### `height`
The height of the target surface

| Type   | Required |
|:------:|:--------:|
| number | No       |

<a name="visible" />
#### `visible`
The visibility of the object

| Type   | Required |
|:------:|:--------:|
| bool   | No       |
