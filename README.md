# templates
Here is weblog templates for BeeBlog.org

## Tags & Templates Guide

Making custom changes to your template is easy, but you will need to know how to
use weblog tags. These tags work with the HTML in your template to create the
content on your weblog.

## How Variables Work
Variables begin with <% and end with %>. They can be used to output various
bits of content on your weblog. For example, placing <%Title%> in your template
will output the title of your weblog. Tags begin with <> and end with </>. Any
content between them is modified in some way, or looped over and outputted
multiple times. For example, placing <Entry><%EntryTitle%></Entry> in your
template will display the title of each of your entries.

## Tags & Variables List

`<%WindowTitle%>` - Weblog title and current page title.
