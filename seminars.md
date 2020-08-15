## Past Seminars

You can find a list of past seminars with a link to the paper presented and a video recording of the seminar if available.


<table width="100%" cellspacing="5" cellpadding="5">

{% for speaker in site.data.speakers %}
<tr>
  <td colspan="2" height="40" valign="top" class="session"><strong>Date: {{ speaker.Date }}</strong></td>
</tr>
<tr>
  <td colspan="2" height="40" valign="top" class="chair">Presenter: {{ speaker.Presenter }}</td>
</tr>
<tr>
  <td colspan="2" height="40" valign="top" class="registration"><a href="{{ speaker.Registration }}">Registration link</a></td>
</tr>
<tr>
  <td width="150" valign="top" class="time">{{ speaker.Time }}</td>
   <td height="30" valign="top" class="paper"><a href="{{ speaker.Paper }}">"{{ speaker.Title }}"</a></td>
</tr>


 {% endfor %}
</table>


</table>
