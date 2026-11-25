# System Conference Deadlines

Live countdown to the paper deadlines of the conferences I keep track of. All are real-time, embedded or
systems venues that have a BK21+ IF in [Pusnow's list of top CS conferences](https://gist.github.com/Pusnow/6eb933355b5cb8d31ef1abcb3c3e1206).

Single static `index.html` — open in a browser, or visit the deployed page:
<https://hanchanghun.github.io/System-Conference-Deadline/>.

## Tracked conferences

| Conference | BK21+ IF | Source |
|------------|----------|--------|
| MobiSys | 3 | <https://www.sigmobile.org/mobisys/2027/call_for_papers/> |
| MobiCom | 4 | <https://sigmobile.org/mobicom/2027/cfp.html> |
| OSDI | 4 | <https://www.usenix.org/conference/osdi27/call-for-papers> |
| ATC (ACM SIGOPS, successor to USENIX ATC) | 3 (USENIX ATC) | <https://atc.sigops.org/2027/call-for-papers/> |
| EMSOFT (ESWEEK) | 2 | <https://esweek.org/emsoft_cfp/> |
| SOSP | 4 | <https://sigops.org/s/conferences/sosp/2026/cfp.html> |
| ASPLOS | 4 | <https://www.asplos-conference.org/> |
| EuroSys | 2 | <https://2027.eurosys.org/cfp.html> |
| RTSS | 4 | <https://2026.rtss.org/> |
| SenSys | 3 | <https://sensys.acm.org/2027/> |
| RTAS | 2 | <https://2027.rtas.org/cfp/> |
| DAC | 3 | <https://dac.com/2027/program/research-manuscript-submissions> |

When a conference's latest deadline has passed, the next edition is listed. Venues with two deadlines a
year (MobiCom, ASPLOS, EuroSys, SenSys) are listed once per deadline. Entries marked
**estimated** (shown in blue) are derived from the previous edition's deadline and are replaced
with confirmed dates once the official CFP is published.

## Updating a deadline

Edit the `DEADLINES` array in `index.html`. Use the `aoe('YYYY-MM-DD')`
helper for "Anywhere on Earth" deadlines, `pst5pm('YYYY-MM-DD')` for
DAC-style 5 PM Pacific deadlines and `est559pm('YYYY-MM-DD')` for USENIX-style 5:59 PM Eastern deadlines. Drop the `estimated: true` flag once the
official CFP is announced.

## License

MIT &mdash; see [LICENSE](LICENSE).
