// Copyright 2012 Yummy Melon Software LLC
//
// Licensed under the Apache License, Version 2.0 (the "License");
// you may not use this file except in compliance with the License.
// You may obtain a copy of the License at
//
// http://www.apache.org/licenses/LICENSE-2.0
//
// Unless required by applicable law or agreed to in writing, software
// distributed under the License is distributed on an "AS IS" BASIS,
// WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
// See the License for the specific language governing permissions and
// limitations under the License.
//
//  Author: Charles Y. Choi <charles.choi@yummymelon.com>

YmsGradientButton

iOS UIButton subclass featuring plist configured bitmap-free gradients.

NOTE: MAJOR PLIST SPECIFICATION CHANGE

* Added support to define multiple gradients to render per UIControlState.
* Added version to YmsGradientButton property list specification. (Version value set to 1.3)
* YmsGradientButton property list schema more robustly specified.

QUICKSTART: 

* Copy YmsGradientButton.[hm], YmsStyleSheet.h and YmsGradientButton.plist to 
  your project.
* Add the QuartzCore.framework to your project.
* Instantiate a UIButton in Interface Builder. With the identity inspector, 
  set the custom class to YmsGradientButton.
* Configure the gradients of the button for the different UIControlStates 
  normal, highlighted, and disabled in the file YmsGradientButton.plist.
  The settings map to the properties defined in CAGradientLayer.
* You can subclass YmsGradientButton and create a plist with the subclass
  name to create your own custom button.
* YmsGradientButton can also be instantiated programmatically.

NOTES:
* This code is written using ARC. 

Please read the project wiki on GitHub for more information.