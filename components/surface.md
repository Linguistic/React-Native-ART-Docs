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

> Tip: <Surface/> element has default background color.
>
> make it transparent with `style={{ backgroundColor:'transparent' }}` and things below it can be seen.

