# CSS-tricks

Create a dashed line similar to border in background using linear gradients
===========================================================================

.horizontal-dashed-line {
  height: 1px;
  background-image: linear-gradient(90deg, #ccc, #ccc 60%, transparent 60%, transparent 100%);
  background-size: 5px 1px;
  border: none;
}


.vertical-dashed-line {
	height: 100px;
	background-image: linear-gradient(to bottom, #ccc 60%, rgba(255, 255, 255, 0) 60%);
	background-position: left;
	background-size: 1px 5px;
	background-repeat: repeat-y;
}
