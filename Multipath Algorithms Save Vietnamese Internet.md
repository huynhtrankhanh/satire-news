# Multipath Algorithms Save Vietnamese Internet

In the vibrant patchwork of Vietnam's energetic economy, internet connectivity stings like a toothache. When it comes to the grasping claws of international services, the fickle monster that is internet access frequently throws a tantrum. Blame those submarine cables, gathering dust and irreparable issues, waving a long "do-not-disturb" flag over Vietnam's cyber seascape. The result? A gaggle of struggling Vietnamese netizens, their surfing skills cramped by lethargic performance, sluggish downloads, and latencies that could make a sloth cringe.

## The Submarine Cable Situation

To understand the gravity of the problem, one must appreciate the sheer misfortune that befalls Vietnam's submarine cables with almost supernatural regularity. The Asia-Africa-Europe 1 (AAE-1), the Asia Pacific Gateway (APG), and the Intra-Asia (IA) cables have collectively spent more time being repaired than operational, leading industry analysts to question whether the cables are cursed, sentient, or simply allergic to carrying data.

The causes are as varied as they are improbable. Anchors from fishing boats — some of which appear to be magnetically attracted to fiber optic lines — account for roughly 40% of outages. Shark bites, once dismissed as an urban legend, have been officially blamed for at least seven incidents, prompting one Vietnamese ISP to issue a formal diplomatic complaint to the International Shark Council (which does not exist). The remaining outages are attributed to "unknown seabed activity," a phrase that engineers use when they have exhausted all rational explanations and are beginning to suspect Poseidon.

Each cable repair takes approximately 3–6 weeks, during which Vietnamese internet users experience what can only be described as digital time travel — back to the dial-up era. Streaming a 1080p video becomes a multi-day commitment. Video calls freeze so frequently that participants have developed an entirely new sign language to communicate during the lag spikes.

## The ISP Scramble

But let's not descend into despair! Our noble ISPs, the lonely knights of Vietnam's cyber realm, strive hard to mend the tears in the universe during such connectivity crises. It's a scramble, borrowing bandwidth and piggybacking on China's route, starting chats with other countries, territories, and — if the situation is sufficiently desperate — even extra-terrestrial forces for possible backup routes. It's ISP roulette: who will have the golden connection this time? Maybe the mobile guys, or perhaps intermediaries with decent global internet access in some hidden country nook?

The behind-the-scenes negotiations resemble a high-stakes poker game played entirely over laggy Zoom calls. ISP engineers, accustomed to working in crisis mode for roughly 340 days per year, have developed a unique set of survival skills. These include the ability to reroute traffic through five countries in under 10 minutes, a comprehensive mental map of every terrestrial fiber link in Southeast Asia, and an almost preternatural sense for which backup routes will themselves fail within the hour.

Internet users, caught in this frenzied flip-flop circus, must be thoroughly winded. One day, your traffic is routed through Singapore; the next, it's taking a scenic tour through mainland China, picking up an extra 200 milliseconds of latency and a newfound familiarity with the Great Firewall. Some packets have been observed arriving at their destination having traversed routes so circuitous that they technically qualify for frequent flyer miles.

## Enter the Wizard: Multipath Algorithms

But don't we wish there was a wizard's spell to automate this madness?

Prepare for the magical Multipath Algorithms! Hot from the cyber lab — Multipath TCP (MPTCP) and Multipath QUIC (MPQUIC). These tech heroes boast modern congestion control algorithmic capes, designed to pirouette gracefully over multipath moats while simultaneously honoring the sacred end-to-end principle of the internet.

The concept is deceptively simple: instead of relying on a single network path that is almost certainly about to be severed by a fishing trawler, why not use *all* the paths? Just pick a bunch of network cables, cryptically plug them into your PC, add a sprinkle of phone-generated mobile internet, throw in your neighbor's unsecured Wi-Fi for good measure, and leap across every available connection. Comfortably ensconced in the lap of multipath algorithmic logic, you'll bask in optimal load distribution across multiple connections, ensuring never a dull day with your precious online surfing.

### How It Works (We Think)

The inner workings of multipath algorithms are elegantly described by the following oversimplification:

1. **Path Discovery:** The algorithm identifies all available network interfaces on your device. This includes your wired Ethernet, Wi-Fi, mobile data, the Bluetooth tethering from your smartwatch, and — in experimental builds — the infrared port that hasn't been used since 2003.

2. **Congestion Estimation:** Using advanced mathematics that would make Euler weep, the algorithm estimates the congestion level on each path approximately 47 times per second. Paths are scored on a scale from "pristine autobahn" to "submarine cable currently being chewed by a shark."

3. **Packet Distribution:** Data is split across all viable paths according to a scheduling algorithm. The scheduler considers bandwidth, latency, jitter, packet loss, the current phase of the moon, and whether Mercury is in retrograde. Packets are reassembled at the destination in the correct order, a feat that researchers describe as "basically magic."

4. **Failover:** When a path fails — and in Vietnam, it is always a question of *when*, not *if* — traffic seamlessly shifts to the remaining paths. Users may notice a brief moment of reduced speed, or they may not notice at all, depending on how many paths remain and whether they have already lowered their expectations to a level consistent with human dignity.

### Real-World Impact

Early adopters of multipath technology in Vietnam report transformative results. A software developer in Ho Chi Minh City claims that by combining a fiber connection, two 4G SIM cards, a satellite internet terminal, and a directional Wi-Fi antenna pointed at the café across the street, she has achieved an aggregate bandwidth of 150 Mbps — a figure previously thought to be theoretical in the region.

A gaming café owner in Hanoi reports that since deploying MPTCP across his 40 machines, customer complaints about lag have decreased by 60%. The remaining 40% of complaints are attributed to skill issues and are outside the scope of network engineering.

## Economic Implications

Call it the productivity booster shot for Vietnam's industrious worker bees, a surefire way to push the GDP into an enviable upward trajectory. Government economists, having modeled the impact of reliable internet on the Vietnamese economy, project a 3.7% increase in GDP growth — a figure they arrived at by "extrapolating aggressively and assuming no further submarine cable incidents," which is roughly equivalent to assuming no further weather in the Pacific Ocean.

The Ministry of Information and Communications has announced a bold new initiative: Project MultiPath 2030, which aims to equip every Vietnamese household with at least four independent internet connections by the end of the decade. The program will be funded by a combination of government bonds, international aid, and the fines collected from fishing boats that anchor on submarine cables.

Critics have pointed out that building redundant terrestrial fiber infrastructure might be a more reliable long-term solution. These critics have been politely asked to leave the conference room.

## Conclusion

In a country where submarine cables have the structural integrity of wet tissue paper and the operational lifespan of a mayfly, multipath algorithms represent not merely a technical improvement but a fundamental shift in the relationship between the Vietnamese people and the internet. No longer must an entire nation hold its collective breath each time a ship drops anchor in the South China Sea. With multipath, the internet doesn't just survive — it thrives, routing around damage with the quiet determination of water finding its way downhill.

As for the sharks, they remain at large. No arrests have been made.
