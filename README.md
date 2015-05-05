This tool is to help calculate the benefits of arp.
Given the non-linear nature of armor damage reduction, X arp will mean different things at 0 arp and 4810 arp (all basic debuffs and executioner applied).

tldr: the soft cap of item arp is 1390.<br>
This is when a boss with 6200 armor has none left after all debuffs, executioner and item arp has been applied.
At this point you will do 58.73% more damage against a 6200 boss and 51.42% more against a 7700 boss, compared to no arp at all.<br>
For reference, this is (kinda) the same as stacking 100% crit chance.

Terminology:</br>
Absolute: your damage increase compared to no arp.</br>
Relative: given all arp; your damage increase by adding X new arp.</br>

<table>
	<tr>
		<th colspan="3">Armor<br></th>
		<th colspan="2">6200</th>
		<th colspan="2">7700</th>
	</tr>
	<tr>
		<td>debuff</td>
		<td>arp</td>
		<td>cumulative arp</td>
		<td style="text-align:center">rel<br></td>
		<td style="text-align:center">abs<br></td>
		<td style="text-align:center">rel<br></td>
		<td style="text-align:center">abs</td>
	</tr>
	<tr>
		<td>5xSunder</td>
		<td>2600</td>
		<td>2600</td>
		<td style="text-align:right">18.36%</td>
		<td style="text-align:right">18.36%</td>
		<td style="text-align:right">16.60%</td>
		<td style="text-align:right">16.60%</td>
	</tr>
	<tr>
		<td>Fearie Fire<br></td>
		<td>610</td>
		<td>3210</td>
		<td style="text-align:right">04.50%</td>
		<td style="text-align:right">23.70%</td>
		<td style="text-align:right">04.10%<br></td>
		<td style="text-align:right">21.30%<br></td>
	</tr>
	<tr>
		<td>CoR</td>
		<td>800</td>
		<td>4010</td>
		<td style="text-align:right">06.28%</td>
		<td style="text-align:right">31.46%</td>
		<td style="text-align:right">05.62%</td>
		<td style="text-align:right">28.15%</td>
	</tr>
	<tr>
		<td>Executioner</td>
		<td>800</td>
		<td>4810</td>
		<td style="text-align:right">06.70%</td>
		<td style="text-align:right">40.26%</td>
		<td style="text-align:right">05.95%</td>
		<td style="text-align:right">35.77%</td>
	</tr>
</table>

Ex. you win Stormrage Signet Ring (http://db.hellground.net/?item=32497, 126 arp) one day, how much benefit does the arp give you?
<table>
	<tr>
		<th colspan="2">Armor<br></th>
		<th colspan="2">6200</th>
		<th colspan="2">7700</th>
	</tr>
	<tr>
		<td>comment</td>
		<td>cumulative arp</td>
		<td style="text-align:center">rel<br></td>
		<td style="text-align:center">abs<br></td>
		<td style="text-align:center">rel<br></td>
		<td style="text-align:center">abs</td>
	</tr>
	<tr>
		<td>all debuffs + executioner</td>
		<td>4936</td>
		<td style="text-align:right">01.07%</td>
		<td style="text-align:right">41.75%</td>
		<td style="text-align:right">00.95%</td>
		<td style="text-align:right">37.05%</td>
	</tr>
</table>


For completeness; the numbers on expose armor.
Here we assume 2/2 improved expose armor and that it replaced 5xsunder, giving it an arp of 475.

<table>
	<tr>
		<th colspan="2">Armor<br></th>
		<th colspan="2">6200</th>
		<th colspan="2">7700</th>
	</tr>
	<tr>
		<td>comment</td>
		<td>cumulative arp</td>
		<td style="text-align:center">rel<br></td>
		<td style="text-align:center">abs<br></td>
		<td style="text-align:center">rel<br></td>
		<td style="text-align:center">abs</td>
	</tr>

	<tr>
		<td>all debuffs</td>
		<td>4485</td>
		<td style="text-align:right">03.87%</td>
		<td style="text-align:right">36.55%</td>
		<td style="text-align:right">03.45%</td>
		<td style="text-align:right">32.56%</td>
	</tr>
	<tr>
		<td>all debuffs + executioner</td>
		<td>5285</td>
		<td style="text-align:right">04.14%</td>
		<td style="text-align:right">46.07%</td>
		<td style="text-align:right">03.66%</td>
		<td style="text-align:right">40.74%</td>
	</tr>

	<tr>
		<td>the last 475 arp for a 6200 boss</td>
		<td>5725</td>
		<td style="text-align:right">04.50%</td>
		<td style="text-align:right">58.73%</td>
		<td style="text-align:right">03.94%</td>
		<td style="text-align:right">51.42%</td>
	</tr>

	<tr>
		<td>the last 475 arp for a 7700 boss</td>
		<td>7225</td>
		<td style="text-align:right">00.00%</td>
		<td style="text-align:right">58.73%</td>
		<td style="text-align:right">04.50%</td>
		<td style="text-align:right">72.93%</td>
	</tr>

</table>
