#Options

<table width="100%"   align="center"  class="table_border_both">
<tr class="heading_table_top">
	<th> Parameter </th>
    <th>  </th>
    <th>Description </th>
	</tr>
	<tr>
<td> -h </td>		
<td> --help </td>
<td>  Print this help text and exit </td>
</tr>
<tr>
<td> --version  </td>
<td> </td>
<td> Print program version and exit </td>
</tr>
<tr>
<td> -U</td>
<td> --update </td>
<td> Update this program to latest version. Make sure that you have sufficient permissions (run with sudo if needed) </td>
</tr>
<tr>
<td>  -i</td>
<td> --ignore-errors</td>
<td>  Continue on download errors, for example to skip unavailable videos in a playlist</td>
</th>
<tr>
<td>--abort-on-error</td>
<td> </td>
<td> Abort downloading of further videos (in the playlist or the command line) if an error occurs</td>
</th>
<tr>
<td> --dump-user-agent </td>
<td> </td>
<td>  Display the current browser identification</td>
</th>
<tr>
<td> --list-extractors </td>
<td> </td>
<td> List all supported extractors</td>
</th>
<tr>
<td> --extractor-descriptions </td>
<td> </td>
<td> Output descriptions of all supported extractors</td>
</th>
<tr>
<td> --force-generic-extractor</td>
<td> </td>
<td> Force extraction to use the generic extractor</td>
</th>
<tr>
<td>  --default-search PREFIX </td>
<td> </td>
<td> Use this prefix for unqualified URLs. For example "gvsearch2:" downloads two videos from google videos for youtube-dl "large apple". Use the value "auto" to let youtube-dl guess ("auto_warning" to emit a warning when guessing). "error" just throws an error. The default value "fixup_error" repairs broken URLs, but emits an error if this is not possible instead of searching.</td>
</th>
<tr>
<td> --ignore-config  </td>
<td> </td>
<td>  Do not read configuration files. When given in the global configuration file /etc/youtube-dl.conf: Do not read the user configuration in ~/.config/youtube-dl/config (%APPDATA%/youtube-dl/config.txt on Windows)</td>
</th>
<tr>
<td>  --config-location PATH </td>
<td> </td>
<td> Location of the configuration file; either the path to the config or its containing directory.</td>
</th>
<tr>
<td>--flat-playlist </td>
<td> </td>
<td> Do not extract the videos of a playlist, only list them. </td>
</th>
<tr>
<td> --mark-watched</td>
<td> </td>
<td> Mark videos watched (YouTube only)</td>
</th>
<tr>
<td> --no-mark-watched </td>
<td> </td>
<td>  Do not mark videos watched (YouTube only)</td>
</th>
<tr>
<td>  --no-color </td>
<td> </td>
<td> Do not emit color codes in output</td>
</th>
</table>
