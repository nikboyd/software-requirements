## Instrument

In the context of this [model](../domain-inventory.md), an [instrument][instrument]

<img align="right" src="../images/instrument_measures.svg" />

<ul>
 <li><i>measures</i> an <a href="activity.md">activity</a> and a <a href="quality.md">quality</a></li>
 <li> </li>
 <li> </li>
 <li> </li>
 <li> </li>
 <li> </li>
 <li> </li>
 <li> </li>
 <li> </li>
 <li> </li>
 <li> </li>
 <li> </li>
 <li> </li>
</ul>



### Discussion

Instruments measure [activities][activity], mainly through counters or averaged rates (typically over time), or reported events.
Within a software [solution][solution], [instruments][instrument] will report their data points through some kind of telemetry,
which may include event logging, or a regular report with a "heart beat".
Downstream systems can then analyze the data provided for patterns and produce alerts and alarms, for example
when some critical threshold is crossed.


<div align="center"><b>&sect; &sect; &sect;</b></div>

[activity]: activity.md
[activities]: activity.md
[business]: business.md
[businesses]: business.md
[component]: component.md
[components]: component.md
[developer]: developer.md
[developers]: developer.md
[dialog]: dialog.md
[dialogs]: dialog.md
[expector]: expector.md
[expectors]: expector.md
[feature]: feature.md
[features]: feature.md
[governor]: governor.md
[governors]: governor.md
[improvement]: improvement.md
[improvements]: improvement.md
[instrument]: instrument.md
[instruments]: instrument.md
[interface]: interface.md
[interfaces]: interface.md
[mission]: mission.md
[missions]: mission.md
[requestor]: requestor.md
[requestors]: requestor.md
[solution]: solution.md
[solutions]: solution.md
[stakeholder]: stakeholder.md
[stakeholders]: stakeholder.md
[value]: value.md
[values]: value.md
[vision]: vision.md
[visions]: vision.md

[qualities]: https://educery.dev/papers/modeling/quality-alignment/#business-quality-inventory
[improve]: improvement.md
[measurement]: https://educery.dev/papers/software-requirements/policy/values/#qualities-quantities
[improves]: improvement.md
[quality]: https://educery.dev/papers/modeling/quality-alignment/#business-quality-inventory
[measurable.way]: measurement.md
[valuable]: value.md
