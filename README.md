# Property Order in CSS

Observe a certain order of styles for the convenience and readability of the code. Positioning properties come first, then block model properties, then fonts. At the very end, other styling and animations.

<code>
  
    .element {
      /* Positioning */
      position: relative;
      left: 0;
      right: 0;
      top: 0;
      bottom: 0;

      /* Block model */
      display: flex;
      align-items: center;
      margin: 10px;
      padding: 10px 20px;
      border: 1px solid red;
      width: 200px;
      height: 100px;
      box-sizing: border-box;

      /* Fonts */
      font-family: Arial;
      font-size: 25px;
      font-style: italic;
      text-decoration: none;
      color: red;

      /* Styling */
      background: red;
      opacity: 1;

      /* Animations */
      transform: translateX(5px);
      animation: shake 0.3s infinite;
    }

</code>
