# Frontend Mentor challenge- Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62).

### 還不熟悉的地方

- Flexbox 排版(對齊、縮放)
- relative 與 absolute 關係
- order
- overlay 方法與效果

```css
.image-overlay::after {
  position: absolute;
  content: "";
  top: 0;
  right: 0;
  width: 100%;
  height: 100%;
  background-color: hsl(277, 64%, 61%);
  mix-blend-mode: multiply;
}
```
