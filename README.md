Montana Mendy's Sublime Configurations
======================

Montana Mendy's Sublime Text configuration files

## The following files include

* Default (OSX).sublime-keymap
* Preferences.sublime-settings
* Standard-comment.sublime-snippet
* CoffeeScript-Configuration
  * coffee-method.sublime-snippet
* Rails
  * rails-logger.sublime-snippet
  * rails-method.sublime-snippet
* Sass

## rails-logger.sublime-snippet
trigger: 'log', tab

produces:
<pre>
  Rails.logger.info "label: #{to_log.inspect}"
</pre>

## rails-method.sublime-snippet
trigger: 'def', tab

produces:
<pre>
  # ==== Parameters:
  # param:: Class
  #
  # ==== Returns:
  # returns
  def method_name arguments
    # code here
  end
</pre>

## standard-comment.sublime-snippet
trigger: 'comment', tab

Works with the following:

* PHP
* Rails
* JavaScript
* ActionScript
* Java

Produces:

<pre>
   * ==== Parameters:
   * param:: Class
   *
   * ==== Returns:
   */ returns
</pre>

## coffee-method.sublime-snippet
trigger: 'c-', tab

Produces:

<pre>
  # ==== Parameters:
  # param:: Class
  #
  # ==== Returns:
  # returns
  method_name = (arguments) ->
    # code here
</pre>
