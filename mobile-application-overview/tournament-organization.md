# Tournament Organization

Ignite Tournaments was built for gamers, professional tournament organizers, guilds, and game publishers. The tournament organization functions allow the organizer to access professional tournament organization tools and hyper-granular settings that enables the end user to design tournaments of any level of complexity.

#### Organization Features <a href="#_2jxsxqh" id="_2jxsxqh"></a>

* Multiple tournament formats: time trials, control point, single and double elimination, round-robin, and more.
* Organizer-defined entry fees and optional organizational fees.
* Unlimited prize splits.
* Multiple tournament formats: player vs player; guild vs. guild; team vs. team tournaments.
* Customizable tournaments with the tournament organizer’s branding and logos.
* Sponsored prizing, to allow sponsors to contribute funds and NFTs to prize pools
* Geofencing to create regional tournaments and determine which countries/regions may participate in your games.

![](../.gitbook/assets/6)

When creating a tournament, the organizer will pick the game, choose a tournament name, add a description, as well as establish the rules of the tournament. The organizer may optionally also opt to charge a tournament organization fee, such as a flat amount of TENKA or a percentage of the prize pool (currently capped at 0.5% maximum.)

Tournaments will initially have a minimum and a maximum number of participants. Tournaments will not start until the minimum number of confirmed participants is reached. Tournaments have a starting date and time, and participation may be restricted based on country/region/state or tier level, based on NFTs held in a user’s NFT wallet. As the product continues to develop, the development team will remove the limit on the maximum number of competitors, to support activities such as massive round robin tournaments.

Rules, entry fee, and prize pool distribution are established at the start of a tournament by the organizer. The organizer will be given the option to close registration a certain period of time before the start of the tournament (e.g., 3 hours, 6 hours, 12 hours, 24 hours).

When there are not enough participants for a tournament, the tournament organizer will be notified and can choose to do one of the following:

1. Alter the date of the tournament to give more time for the participant slots to fill up. In this case, participants will be notified and will be given the option to re-confirm the new scheduled time.
2. Drop the minimum requirement, in this case existing participants will be notified and given the option to reconfirm under the new conditions.
3. Cancel the tournament, in this case existing participants will be notified, and may be given the option to overtake the tournament as the new organizer to ensure the tournament takes place.

Because the platform will support many types of games, tournaments will have a range of conditions different based on the game being played. This will include the duration of the tournament, the duration of matches within a tournament, the number of matches within a tournament, conditions by which a player or group of players moves to a next round as relevant, and many other features.

Timing and scheduling for subsequent rounds in tournaments is also set by the tournament organizer. The platform will give the organizer the option to set rules for subsequent rounds which can be announced to all participants (so that all participants know ahead of time what to expect) as well as the option to set the starting time for subsequent rounds only after previous rounds have been finished, giving players a chance to break and reorganize.

Participants will know ahead of time what the structure, timing, and format of subsequent rounds will be, so that they agree to the nature of the tournament before they participate.

Lastly, the organizer of a tournament will have the option to require approval for new participant registration when a tournament is already under way. This approval process could be carried out by an organizer, a moderator, or a participant, and the system can have a specific internal role which would allow users involved in a tournament to have approval rights. This could be as simple as only allowing organizers to approve registrations, in this case any invitations sent by regular participants would need to be approved by an organizer), and we feel that the system should encourage the organizer to choose this option, since it adds a strong quality control mechanism to the participant pool.

The following concepts are key to the tournament organizational process for the application:

**Entry Fees**

All entry fees will be paid in TENKA.

Organizers will be able to choose which currency they want to see the entry fees and prize pools calculated in (e.g. TENKA valued as USD). Participants would have the option to specify a default currency so that they can view the same tournament entry fees and prize pools in their own currency.

Free tournaments don't have entry fees and may be supported by advertisement revenue.

**Prize Pools**

The prize pool distribution should be set before registration can be opened. The organizer may set the prizes as a percent of the whole pool or as a net amount, to a specific place (1st, 2nd, 3rd) or to a range of final positions in the tournament (6th-12th).

The total prize pool will equal the sum of the entry fees less any predetermined fees from the platform (e.g. 10% platform fee, moderator fee, allocations to other funds, etc.)

Sponsors can also contribute to prize pools in the form of TENKA or NFTs.

**Tips**

Viewers can tip competitors or organizers at any point during the tournament. The list of tips - including their amount, the tipping user and the receiver are public. Tips are automatically closed after the tournament. Tips go directly into the individual's wallet.

**Tournament Formats**

A tournament format refers to the format of the tournament, e.g., how a tournament participant will compete against another tournament participant. Currently in scope, the following tournament formats will be supported:

* 1v1 (Player vs Player “PvP”)
* Team vs Team
* Guild vs Guild

Based on user feedback in multiple iterations of product testing, additional tournament formats may be added in the future.

**Tournament Structures**

A tournament structure refers to the specific structure of competition in which the tournament will be run. Ignite Tournaments will support tournaments such as PvP, control point, time trials, and speed runs, as well as complex tournament structures and bracketing systems.

Tournament structures may include a) bracketed tournaments (both single and double elimination), b) round robin tournaments, and c) mixed tournaments, though the following more specific tournament types may be incorporated shortly after:

* Brackets with predetermined schemes and with random draw after a particular stage
* Brackets with group stages
* Series of tournaments with a shared ranking list
* Bronze tournaments to determine 3rd and 4th place winners.

Depending on tournament type, tournament organizers can place (“seed”) specific competitors into different brackets to compete. For bracketed events, when each bracket finishes their individual matches, the organizer selects a winner of each bracket, and the system will automatically move winners into the next bracket after on-chain consensus voting occurs for non-integrated games. For integrated games, the next match will begin after automated match adjudication occurs. (See Match Adjudication.)

**Registration and Participation**

To take part in a tournament, a user must join/register the tournament. When joining a tournament, the entry fee is either subtracted from the user’s balance or paid directly in the same manner by which a user deposits funds into their account (e.g. credit card payment).

At this time, organizers cannot participate in their own tournaments in non-integrated games, to prevent bias.

**Invitations**

Tournaments can either be public, invite only public, or private. All tournaments that are public are listed in a searchable database. Anyone can view or join if a tournament is public.

After creating a tournament, the organizer (as well as any else they designate as a co-organizer) can send invites to users within and outside the system by:

* Selecting a list of users by their in-app nickname
* Sending invitation via email
* Copying/sharing a tournament code/link

**Starting a Tournament**

After the registration time expires, the tournament scheme is generated based on the number of registered users. The organizer may manually seed individual participants (in a bracketed tournament) or perform a random draw to fill in the remaining spots.

A tournament-match is created for each of the pairs in all the stages with known participants.

Organizers will determine specific rules for how to handle odd numbers of participants (here, "odd" includes also even numbers of participants which aren't powers of 2 for bracketed tournaments.).

**Stages**

Many tournaments will by design be completed in a single stage. However, tournaments may consist of multiple stages with different formats (e.g., round-robin groups stage with only the top X players from each group advancing to a knockout/bracketed stage). Each stage has multiple rounds. Multi-staged tournaments have mixed format by design (a post-MVP feature).

**Rounds**

Each tournament consists of multiple rounds and each round consists of a set of tournament-matches between opponents.

The organizer can determine the window of time allowed for tournament participants to start their play during a given round. In this way, the matches in the round do not need to start at the same time, but are still finished after a reasonable amount of time.

Any participant who does not start play within the allotted time will automatically be recorded as having lost the round by the system.

**Fixtures (tournament-matches)**

A fixture (tournament-match) is an event with two participants (individuals/teams/guilds) playing against each other. A fixture may consist of a single match, or the winner can be decided in a “best of X[ ](https://www.notion.so/Match-318fcd8e3aed4dd295c755d71b68399d)matches” format. In the case of draws, there will be a tie-breaker match(es).

After a tournament-match is played, Ignite Tournaments’ match adjudication process begins. (See Match Adjudication.)

**Winning**

Winning a tournament may mean different things depending on the particular game in which the tournament is played. These rules may also be differently set by the tournament organizer.

For example, in a round robin tournament, the winning status is dependent on points awarded for wins during each tournament-match. Organizers will determine how points are awarded in round robin tournaments in non-integrated games. In integrated games, points awarded will be determined by each individual game.

**Payouts**

After Match Adjudication occurs, the prize pool is split between the contestants based on their placement, and the payouts are sent to individual contestant’s wallets in the form of TENKA and NFTs.

**Scheduling**

The platform will support an in-app view for participants to view upcoming tournaments, and may also in the future include an integration to external calendar applications (e.g. Google Calendar).

#### User Categories <a href="#_92jejsid19gb" id="_92jejsid19gb"></a>

Throughout the entirety of the Ignite Tournaments application, multiple categories of users will be expected to interact with the application. Please see below a breakdown of the primary user categories, their relevant use cases with the application, and how they relate to one another.

**Tournament Participants**

The primary user on the Ignite platform, tournament participants are the actual entrants into the particular tournaments. Participants pay entry fees in order to enter into and compete in a tournament of the game of their choosing.

**Tournament Organizers**

Tournament organizers set the conditions and specifications of a tournament in which participants enter in order to compete. Organizers may coordinate with hosts, sponsors of a particular tournaments, teams, and guilds to structure a tournament according to an agreed set of rules.

At the conclusion of a tournament, in order for prize payouts to occur, the tournament organizer’s first job is to select the winner.

**Hosts**

Hosts are a restricted type of tournament admins that can approve match results and settle disputes between players. Organizers can invite hosts after creating a tournament.

Hosts are optional for now - tournaments can exist without them, where the organizer acts as the moderator.

**Teams**

Some games supported by the platform will be team-based or have some types of gameplay which are team-based.

The platform will support the creation and maintenance of teams, whereby one user can create a team and remains as the team organizer/maintainer (and invite others to help share the responsibility), and take actions such as entering the team into tournaments, etc.

Teams will be searchable on the platform so long as the team is listed as public (optionally specified by the team organizer).

Team payouts will be handled simply by splitting payouts equally across the team members. Later, the platform will support functionality where team balances can be maintained in a team wallet, which can be distributed according to rules, team consensus, or governance members chosen by the team.

Team pages will maintain information about membership and competition history, etc.

**Guilds**

Guilds are collectives of gamers coming together to game competitively with and against each other. Guilds will be able to compete against other guilds in guild vs guild tournaments that will be supported by the platform.

Please see Guild Management System for more information on Guilds.

#### Match Adjudication <a href="#_3j2qqm3" id="_3j2qqm3"></a>

**Non-integrated Games**

For non-integrated games, matches are adjudicated by the tournament organizer, where the results are validated via on-chain consensus voting by users. After the organizer selects the winner and receives a majority confirmation from voters, Ignite Tournaments will update the blockchain with the winner. Then, the next match will proceed, or the tournament will conclude and payouts will occur after a compliance process.

If only a minority agree, the tournament organizer will be notified and given the choice between recasting the vote or opening a dispute.

_(A dispute will automatically be opened if players fail to reach consensus on the second vote or if the organizer fails to choose within n minutes.)_

**Integrated Games**

For games that have integrated with Ignite Tournaments, matches will be adjudicated via automated match adjudication using either on-chain data validation or an oracle to offer a fully trustless, decentralized tournament adjudication and payout process.

### &#x20;<a href="#_7lxldgv8yya3" id="_7lxldgv8yya3"></a>
