WHAT?

This vim plugin allows you to run the test/spec that your cursor currently 
sits on, and ONLY that test/spec. It will ignore all other tests/specs in 
the current file.

This plugin currently supports
  - test/unit
  - dust
  - rspec

HOW?

Simply place your cursor within the test/spec you want to run and execute
:RunRubyFocusedUnitTest. Feel free to map this command for convenience. 

INSTALL

Just copy ruby_focused_unit_test.vim into ~/.vim/plugin. That's it!

REQUIREMENTS

- vim with ruby support (compiled +ruby)

