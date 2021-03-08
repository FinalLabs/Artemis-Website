# Credits

```css
/*!
 *
 * bttn.css - https://ganapativs.github.io/bttn.css
 * Version - 0.2.4
 * Demo: https://bttn.surge.sh
 *
 * Licensed under the MIT license - http://opensource.org/licenses/MIT
 *
 * Copyright (c) 2016 Ganapati V S (@ganapativs)
 *
 */
/* standalone - .bttn-minimal */
.bttn-default {
    color: #fff;
  }
  .bttn-primary,
  .bttn,
  .bttn-lg,
  .bttn-md,
  .bttn-sm,
  .bttn-xs {
    color: #1d89ff;
  }
  .bttn-warning {
    color: #feab3a;
  }
  .bttn-danger {
    color: #ff5964;
  }
  .bttn-success {
    color: #28b78d;
  }
  .bttn-royal {
    color: #bd2df5;
  }
  .bttn,
  .bttn-lg,
  .bttn-md,
  .bttn-sm,
  .bttn-xs {
    margin: 0;
    padding: 0;
    border-width: 0;
    border-color: transparent;
    background: transparent;
    font-weight: 400;
    cursor: pointer;
    position: relative;
  }
  .bttn-lg {
    padding: 8px 15px;
    font-size: 24px;
    font-family: 'Montserrat', sans-serif;
  }
  .bttn-md {
    font-size: 20px;
    font-family: 'Montserrat', sans-serif;
    padding: 5px 12px;
  }
  .bttn-sm {
    padding: 4px 10px;
    font-size: 16px;
    font-family: 'Montserrat', sans-serif;
  }
  .bttn-xs {
    padding: 3px 8px;
    font-size: 12px;
    font-family: inherit;
  }
  .bttn-minimal {
    margin: 0;
    padding: 0;
    border-width: 0;
    border-color: transparent;
    background: transparent;
    font-weight: 400;
    cursor: pointer;
    position: relative;
    /*text-shadow: 0px 0px 2px rgb(40, 40, 40); /**/
    font-size: 20px;
    font-family: 'Montserrat', sans-serif;
    padding: 5px 12px;
    overflow: hidden;
    border-width: 0;
    border-radius: 4px;
    background: transparent;
    color: #fff;
    -webkit-transition: all 0.5s cubic-bezier(0.02, 0.01, 0.47, 1);
    transition: all 0.5s cubic-bezier(0.02, 0.01, 0.47, 1);
  }
  .bttn-minimal:after {
    position: absolute;
    bottom: 0;
    left: 10px;
    width: calc(100% - 20px);
    height: 1px;
    background: currentColor;
    content: '';
    opacity: 0.65;
    -webkit-transition: opacity 0.5s cubic-bezier(0.02, 0.01, 0.47, 1), -webkit-transform 0.5s cubic-bezier(0.02, 0.01, 0.47, 1);
    transition: opacity 0.5s cubic-bezier(0.02, 0.01, 0.47, 1), -webkit-transform 0.5s cubic-bezier(0.02, 0.01, 0.47, 1);
    transition: transform 0.5s cubic-bezier(0.02, 0.01, 0.47, 1), opacity 0.5s cubic-bezier(0.02, 0.01, 0.47, 1);
    transition: transform 0.5s cubic-bezier(0.02, 0.01, 0.47, 1), opacity 0.5s cubic-bezier(0.02, 0.01, 0.47, 1), -webkit-transform 0.5s cubic-bezier(0.02, 0.01, 0.47, 1);
  }
  .bttn-minimal:before {
    position: absolute;
    bottom: 0;
    left: 10px;
    width: calc(100% - 20px);
    height: 1px;
    background: currentColor;
    content: '';
    opacity: 0.65;
    -webkit-transition: opacity 0.5s cubic-bezier(0.02, 0.01, 0.47, 1), -webkit-transform 0.5s cubic-bezier(0.02, 0.01, 0.47, 1);
    transition: opacity 0.5s cubic-bezier(0.02, 0.01, 0.47, 1), -webkit-transform 0.5s cubic-bezier(0.02, 0.01, 0.47, 1);
    transition: transform 0.5s cubic-bezier(0.02, 0.01, 0.47, 1), opacity 0.5s cubic-bezier(0.02, 0.01, 0.47, 1);
    transition: transform 0.5s cubic-bezier(0.02, 0.01, 0.47, 1), opacity 0.5s cubic-bezier(0.02, 0.01, 0.47, 1), -webkit-transform 0.5s cubic-bezier(0.02, 0.01, 0.47, 1);
  }
  .bttn-minimal:hover,
  .bttn-minimal:focus {
    /*  text-shadow: 0px 0px 0px rgb(40, 40, 40); /**/
    opacity: 0.9;
  }
  .bttn-minimal:hover:after,
  .bttn-minimal:focus:after {
    opacity: 1;
    -webkit-transform: translateX(-10px) rotate(0.001deg);
            transform: translateX(-10px) rotate(0.001deg);
  }
  .bttn-minimal:hover:before,
  .bttn-minimal:focus:before {
    opacity: 1;
    -webkit-transform: translateX(10px) rotate(0.001deg);
            transform: translateX(10px) rotate(0.001deg);
  }
  .bttn-minimal.bttn-xs {
    padding: 3px 8px;
    font-size: 12px;
    font-family: 'Montserrat', sans-serif;
  }
  .bttn-minimal.bttn-sm {
    padding: 4px 10px;
    font-size: 16px;
    font-family: 'Montserrat', sans-serif;
  }
  .bttn-minimal.bttn-md {
    font-size: 20px;
    font-family: 'Montserrat', sans-serif;
    padding: 5px 12px;
  }
  .bttn-minimal.bttn-lg {
    padding: 8px 15px;
    font-size: 30px;
    font-family: 'Montserrat', sans-serif;
  }
  .bttn-minimal.bttn-default {
    color: #fff;
  }
  .bttn-minimal.bttn-primary {
    color: white;
  }
  .bttn-minimal.bttn-warning {
    color: rgb(255, 255, 255);
    font-weight: bold;
  }
  .bttn-minimal.bttn-danger {
    color: #ff5964;
  }
  .bttn-minimal.bttn-success {
    color: #28b78d;
  }
  .bttn-minimal.bttn-royal {
    color: #bd2df5;
  }
```

# Liscence

MIT License

Copyright (c) 2021 FinalLabs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
