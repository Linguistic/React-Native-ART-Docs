# Group
Combines Shapes or other Groups into hierarchies that can be transformed as a set.

```js
render() {
    return (
        <Surface>
            <Group x={0} y={0}>
                <Shape/>            
                <Shape/>
            </Group>
            <Shape/>
        </Surface>
    )
}
```

#### Props

- [`x`](#x)
- [`y`](#y)

## Reference

### Props

<a name="x" />
#### `x`
X-coordinate of the group starting from the top-left corner

| Type   | Required |
|:------:|:--------:|
| number | No       |

<a name="y" />
#### `y`
X-coordinate of the group starting from the top-left corner

| Type   | Required |
|:------:|:--------:|
| number | No       |