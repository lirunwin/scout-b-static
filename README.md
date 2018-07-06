

## Requirements
[x] need <b>node.js</b> pre-installed and you’re good to go.

## Todo List
[ ] Find a css freamwork built with sass/scss to work with.
  [x] icons
  [ ] set up color and space stuff
    [ ] color
      $primary: {
        color: #9fb584,
        dark: #83976b,
        light: #a7b498
      }
      $accent: {
        color: #fec821
      }
      $input-border-color: map-get($primary, color);
      $input-bg-color: #f9f9f9;
      $border-color: #f1f1f1;
      $border-radius: 4px;
      $box-shadow: 0 0 5px rgba(map-get($primary, color), 0.25);

[ ] Import iconfont

[ ] Built components
  [ ] Buttons
  [ ] Inputs
  [ ] Radio & Checkbox
  [ ] Nav
  [ ] Sidebar
  [ ] Tables
  [ ] Modal
  [ ] Cards
  [ ] Tollbar

[ ] Pages
  [ ] Index.html

  [ ] SignUp.html

  [ ] Post.html
    [ ] Parttime

  [ ] Processing.html
    [ ] detail tab
      [ ] tab & dropdown
      [ ] mission info
      [ ] review
        [ ] solo apply
        [ ] team apply
        [ ] request delay
      [ ] recruit list
      [ ] invite
        [ ] from system
        [ ] from recruits
      [ ] modal
      [ ] pagination
    [ ] resume

  [ ] Done.html

  [ ] Cancel.html

  [ ] Mission.html
    [ ] detail
    [ ] bouns modal
    [ ] team member modal
    [ ] comment

  [ ] RejectMission.html

  [ ] Salary.html

  [ ] SalaryLog.html

  [ ] Deposit.html

  [ ] Profile.html

  [ ] Account.html
    [ ] change password
    [ ] change mobile phone
    [ ] bind phone number

  [ ] Help.html

  [ ] About.html

  [ ] Privacy.html

  [ ] UserAgreement.html


## [webpack](https://webpack.js.org/)
If you're not familiar with webpack, the [webpack-dev-server](https://webpack.js.org/configuration/dev-server/) will serve the static files in your build folder and watch your source files for changes.
When changes are made the bundle will be recompiled. This modified bundle is served from memory at the relative path specified in publicPath.
