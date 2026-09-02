### Section 4: Description — AI Ko Wo Sab Kuch Batao Jo Usay Chahiye

**Simple Explanation**

Yaad karo course ki shuruat mein wo colleague jiska course outline galat nikla tha? Uski ghalti isliye hui kyunke tumne usay zaroori information nahi di thi. AI ka masla isse bhi zyada gehra hai — woh tumhara zehn (mind) parh nahi sakta. Woh sirf usi information se kaam karta hai jo usay di jaye. Agar tum koi important cheez chhor do, AI ek "reasonable guess" (mantiqi andaza) laga sakta hai — lekin wo andaza galat bhi ho sakta hai.

**Description ka matlab hai AI ko wo information aur guidance dena jo usay kaam achi tarah karne ke liye chahiye.** Yeh sirf "acha prompt likhna" se bohat zyada bara concept hai. Ismein teen cheezein shamil hain: **Product description** (tumhein kya chahiye), **Process description** (kaam kis tareeqay se ho), aur **Performance description** (AI kis tarah behave (rawaiya) karay).

**Product description** yeh sawal poochti hai: "mujhe wapas exact kya chahiye?" Ismein shamil hai: output ka type, audience, format, length, tone, important topics, aur kya chhorna hai. Ek vague request hai "is report ko summarize karo." Ek clearer request hai: "is quarterly financial report ko senior executives ke liye summarize karo jinke paas parhne ke liye sirf 10 minute hain. Revenue trends, major risks, aur recommended actions per focus karo. Short bullet points use karo aur ek page tak mehdood rakho." Doosri request zyada intelligent nahi — bas zyada **complete** hai. Yaad rakho: **completeness usually cleverness se zyada matter karti hai.**

**Process description** yeh sawal poochti hai: "AI ko kaam kaise karna chahiye?" Jaisay steps, order, method, examples, ya finish karne se pehle checks. Jab kaam ke kai stages hon, process description bohat zaroori ho jati hai. Misaal ke taur per, agar teen vendors ke proposals hain, to poora kaam ek hi sath (extract, compare, score, recommend) mangna khatarnak hai kyunke sirf ending check ho sakti hai. Behtar tareeqa hai: har step alag se karwao aur agle step se pehle check karo. Sabse pehle extraction karwao, kyunke agar wahan ghalti hui to woh comparison, scoring, aur final draft mein bhi chal jayegi.

**Performance description** yeh sawal poochti hai: "AI kis tarah behave karay, aur kiske liye?" Jaisay AI concise ho ya detailed, supportive ho ya challenging, sawal pehle poochay ya reasonable assumptions banaye. Ek useful performance description ho sakti hai: "mere weak assumptions ko challenge karo, uncertainty flag karo, sirf politeness ke liye mujh se agree mat karo." Chhoti scale per yeh sirf tumhare working-style preferences hain. Lekin bari scale per (jab tum AI system deploy karte ho doosron ke liye) yeh performance description hi wo "rule" ban jati hai jo hazaron logon per apply hoti hai jinhe tum kabhi nahi milogay.

Description ka aik aur bara idea hai **context engineering** — sirf "message kaise likhoon" nahi balkay "AI ke kaamyaab honay ke liye kya kya information available honi chahiye?" Ismein documents, examples, memory, policies, tools, definitions sab shamil hain. Ek khoobsurat prompt bhi kisi aisay agent ko nahi bacha sakta jiske paas ghalat data ya missing rules hon.

**Important Points**
* Description = AI ko kaam achi tarah karne ke liye zaroori information aur guidance dena.
* Teen hissay: **Product** (kya chahiye), **Process** (kaise karna hai), **Performance** (kaise behave karay).
* Yaad rakhne ka tareeqa: **What → How → How to work with me**.
* "Completeness usually beats cleverness" — mukammal hona clever hone se zyada zaroori hai.
* Jab kaam ke kai stages hon, ek-ek step karwao aur beech mein check karo — sabse pehle wo step jiski ghalti sabse zyada aagay tak phailay.
* Chhotay scale per Performance description tumhara preference hai; bade scale per yeh deployed agent ka "product" ban jati hai.
* **Prompt engineering** poochta hai "message kaisay likhoon", jabkeh **Context engineering** poochta hai "AI ke success ke liye kya information available honi chahiye."

**Difficult Words**
* Description → AI ko zaroori information dena taake woh kaam sahi tarah karay.
* Product description → Output (natija) ka exact ta'aruf — kya chahiye.
* Process description → Kaam karne ka tareeqa aur steps.
* Performance description → AI ka rawaiya (behavior) kaisa ho.
* Context engineering → AI ke liye zaroori tamam information design karna (sirf message ki wording nahi).

**Quick Revision**
Description ka matlab hai AI ko sirf ek prompt nahi, balkay teen cheezein dena: kya chahiye (product), kaise karna hai (process), aur kaise behave karna hai (performance). "What → How → How to work with me" is teeno ko yaad rakhne ka tareeqa hai. Mukammal information dena, clever wording se zyada important hai. Bade multi-step kaamon mein har step ko alag karo aur check karo, kyunke pehle step ki ghalti aagay tak phail jati hai. Bari scale per, performance description hi deployed agent ka asal rawaiya ban jati hai.
