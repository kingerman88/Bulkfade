# Bulkfade
A simple module to help bulk-tween UI elements.
[Tutorial](https://youtu.be/FPOsnZrRD0U)

# Documentation

## Functions

### <strong>CreateGroup</strong>
Creates a new tween group

```
BulkFade.CreateGroup(
    elements: {<Instance>},
    tweenConfig?: TweenInfo
) -> BulkFadeGroup
```
## Methods

### <strong>GetElements</strong>
Simply returns all the elements in the tweengroup

```
BulkFade:GetElements() -> {<GuiObject>}
```

### <strong>FadeIn</strong>
Calls all the tweens (in)

```
BulkFade:FadeIn() -> nil
```

### <strong>FadeOut</strong>
Calls all the tweens (out)

```
BulkFade:FadeOut() -> nil
```

### <strong>Fade</strong>
Calls all the tweens (in/out toggle)

```
BulkFade:Fade() -> nil
```