# Messages Widget for [Smashing](https://smashing.github.io)

[Smashing](https://smashing.github.io) widget that displays that displayd detailed messages from other widgets.
Out of the box it works with the [Veeam Widget](https://github.com/lucapxl/smashing_widget_veeam) and the [Nagios XI Widget](https://github.com/lucapxl/smashing_widget_nagiosxi)

## Example

![exmaple1](https://raw.githubusercontent.com/lucapxl/smashing_widget_messages/master/images/messages-1.png)
![exmaple2](https://raw.githubusercontent.com/lucapxl/smashing_widget_messages/master/images/messages-2.png)

## Installation and Configuration

messages for this dashboard are HTML string with the following format:

```html
<p class='single-message-header'><i class='fa fa-exclamation-triangle'></i><span>Your message here</span></p>
<p class='single-message-body'>you can add details here, this bit is optional</p>
```

the icons available in this version are:

* fa-exclamation-circle => red colored circle, used for important messages that need immediate attention
* fa-exclamation-triangle => yellow attention triangle, used for warnings that need attention but are less critical
* fa-question => grey color question mark, used for "unknown" messages
* fa-info-circle => blue color, used for general messages

## License

Distributed under the MIT license
