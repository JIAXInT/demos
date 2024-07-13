1.在 js 中，选中的 html 元素都拥有 offsetWidth 和 offsetHeight 属性，上述属性返回它的屏幕尺寸，包含元素的边框和内边距，不包含外边距

2.在 js 中，选中的 html 元素都拥有 clientWidth 和 clientHeight 属性，类似于 offsetWidth 和 offsetHeight，但不包含元素的边框，只包含内容和内边距

3.在 js 中，选中的 html 元素都拥有 offsetTop 和 offsetLeft 属性，以上属性可以返回当前元素距离某个父辈元素左或者上边缘的距离，只读属性。如果父辈元素中有定位元素，那么就返回距离当前元素最近的定位元素边缘的距离。如果父辈元素中没有定位元素，那么就返回距离当前元素最近的非定位祖先元素的边缘的距离，那么就返回相对于 body 边缘距离
