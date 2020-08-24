## Past Seminars

You can find a list of past seminars with a link to the paper presented and a video recording of the seminar if available.


<table width="100%" cellspacing="5" cellpadding="5">

{% for speaker in site.data.speakers %}
<tr>
  <td colspan="2" height="40" valign="top" class="session"><strong>Date: {{ past_seminars.Date }}</strong></td>
</tr>
<tr>
  <td colspan="2" height="40" valign="top" class="chair">Presenter: {{ past_seminars.Presenter }}</td>
</tr>
<tr>
  <td colspan="2" height="40" valign="top" class="registration"><a href="{{ past_seminars.Video }}">Video</a></td>
</tr>
<tr>
  <td width="150" valign="top" class="time">{{ past_seminars.Time }}</td>
   <td height="30" valign="top" class="paper"><a href="{{ past_seminars.Paper }}">"{{ past_seminars.Title }}"</a></td>
</tr>

<tr style="border-bottom:1px solid black">
  <td colspan="100%"></td>
</tr>

 {% endfor %}
</table>
