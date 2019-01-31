# @hemasasi/tiny
Removes all spaces from a string.

# Install

$ npm install @hemasasi/tiny

# Usage

const tiny = require("@hemasasi/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
