## Schedule

The schedule is updated regularly as new seminars are added to the series.
All seminars start at **2:30PM EDT / 1:30PM CDT / 11:30AM PDT**.

<table width="100%" cellspacing="5" cellpadding="5">

{% for speaker in site.data.speakers %}
<tr>
  <td colspan="2" height="40" valign="top" class="session"><strong>Date: {{ schedule.Date }}</strong></td>
</tr>
<tr>
  <td colspan="2" height="40" valign="top" class="chair">Presenter: {{ schedule.Presenter }}</td>
</tr>
<tr>
  <td colspan="2" height="40" valign="top" class="registration"><a href="{{ schedule.Registration }}">Video</a></td>
</tr>
<tr>
  <td width="150" valign="top" class="time">{{ schedule.Time }}</td>
   <td height="30" valign="top" class="paper"><a href="{{ schedule.Paper }}">"{{ schedule.Title }}"</a></td>
</tr>

<tr style="border-bottom:1px solid black">
  <td colspan="100%"></td>
</tr>

 {% endfor %}
</table>
