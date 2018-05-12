Testing 3D CSS Card Flip Effect
-------------------------------

Testing how to implement a CSS3 Card Flip Effect.

### HTML Structure

```html
<div class="card-wrapper {class_effect}">
  <div class="card">
    <div class="front">
      <!-- FRONT SIDE -->
    </div>
    <div class="back">
      <!-- BACK SIDE -->
    </div>
  </div>
</div>
```

### Class Effects

```
.flip-right
.flip-left
.flip-up
.flip-down
.flip-diagonal-right
.flip-diagonal-left
.flip-inverted-diagonal-right
.flip-inverted-diagonal-left
```

### Flip Horizontal (Direction: Right)

```html
<div class="card-wrapper flip-right">
  <div class="card">
    <div class="front">
      FRONT
    </div>
    <div class="back">
      BACK
    </div>
  </div>
</div>
```

Add the width and height of the card:

```css
.card-wrapper, .card {
  width: 200px;
  height: 200px;
}
```
