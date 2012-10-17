# BODY CLASS ATTRIBUTES

# EXAMPLE 1: SIMPLER
# =================================================
# app/views/layout/application.haml
!!!
%html
  %head
  %body{:class => "#{controller_name} #{action_name}"}



# EXAMPLE 2: MORE INFORMATIVE
# =================================================
# app/helpers/application_helper.rb
module ApplicationHelper
  def body_attributes
    { :id => controller_name,
      :class => [action_name, (@body_class if @body_class), ('admin' if in_admin?)].compact * ' ' }
  end

private
  def in_admin?
    not controller.class.name[/^Admin\:\:/].nil?
  end
end

# app/views/layout/application.haml
%body{body_attributes}