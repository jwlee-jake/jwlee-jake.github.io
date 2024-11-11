## EMNLP 2024 Findings
**Session**: NLP Applications 2  
**Date & Time**: Wednesday, Nov 13, 10:30-12:00  
**Location**: Riverfront Hall  

### Poster Title
**Exploring Automated Keyword Mnemonics Generation with Large Language Models via Overgenerate-and-Rank**

#### Criteria
Guidelines for rating on a 5-point Likert scale for imageability, coherence, and usefulness.

##### Imageability

| Scale      | Explanation                                                                                                     |
|------------|-----------------------------------------------------------------------------------------------------------------|
| High (5)   | The sentence evokes a vivid and detailed mental image, making it easy to visualize the scene or situation.      |
| Medium (3) | The sentence evokes a reasonable level of imagery: minor inconsistencies may exist, but a mental image forms.   |
| Low (1)    | The sentence lacks substantial imagery, making it challenging to form any meaningful mental image.              |

##### Coherence

| Scale      | Explanation                                                                                                    |
|------------|----------------------------------------------------------------------------------------------------------------|
| High (5)   | The sentence is highly coherent: the meaning is clear, and the wording is natural.                             |
| Medium (3) | The sentence is moderately coherent: minor issues affect clarity in understanding the meaning.                 |
| Low (1)    | The sentence lacks coherence: it’s difficult to understand or read due to illogical structure or grammar.      |

##### Usefulness

| Scale      | Explanation                                                                                                                       |
|------------|-----------------------------------------------------------------------------------------------------------------------------------|
| High (5)   | The sentence is a useful tool for memorizing the vocabulary word; it effectively aids in remembering or is imagined to aid others.|
| Medium (3) | The sentence has minor issues impacting its usefulness, but it could be helpful with some modifications.                          |
| Low (1)    | This sentence is not useful at all.                                                                                               |

#### Keyword Mnemonics
Table: Verbal cues used for human evaluation. Keywords are represented in italic, while a target word is in bold. An asterisk (\*) indicates an anomaly in verbal cue generation using LLM.

| Word          | LLM-generated                                                                                                               | Human-authored                                                                                                   |
|---------------|-----------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------|
| abstemious    | *Ab*'s diet of only the *stem* of vegetables taught *me* and *us* to be more **abstemious**.                               | *Ab*'s *steamy* with *us* when he tells us to be **abstemious**.                                                 |
| accolade      | The *echo* of the *lad*'s music earned him an **accolade**.                                                                | *A* *coal* *aide* receives an **accolade**.                                                                      |
| aesthetic     | *As* *the* clock *ticked*, he was captivated by the **aesthetic** appeal of the painting.                                 | Oh beautiful *S*! *That* *tick* tickles the **aesthetic** sense!                                                |
| appease       | He cooks *a* dish with *peas* to **appease** her anger.                                                                    | Tom was **appeasing** a pot *o'* *peas*.                                                                        |
| archaic       | The twins wonder "are these *cake* instructions?" from an **archaic** recipe book.                                         | Sick kangaroos ride on **archaic** *Ark* *K* - "*Ick!*" is all they can say.                                    |
| artisan       | In the *art*-loving town, the **artisan** sips his *tea* under the *sun*.                                                  | "*Art* *is* *sin*," says the Puritan to the **artisan**.                                                        |
| ascendancy    | The *ass* and *hen* *dance* by the *sea* to determine their **ascendancy**.                                                | The Egyptians are doing the *Ascend* *Dance* to **ascendancy**.                                                 |
| authoritarian | The citizens of *Ought* face the choice to submit *or* resist the **authoritarian** regime, causing their freedom to *tear* like *rain*. | **Authoritarian** *Arthur* *Tarian* tells Ian to tear up other authors' works.                                  |
| beguile       | A *bee* and a *guy* **beguile** people in each supermarket *aisle* they walk down together.                                | Be Guy well, or *be* *Guy* *ill*, he must **beguile** the nurse from Brazil.                                    |
| censure       | John's *sin* made his mother *sure* to **censure** him.                                                                    | A *cent* with a *sore* **censured** at the Century Bank.                                                        |
| compliance    | Using a *comb* to *ply* his hair, Billy observes *ants'* **compliance** to their queen's orders.                           | "*Come*, *ply* *ants* with honey to gain their **compliance** with our plan."                                   |
| concede       | The *con* man was outsmarted by a humble *seed* seller, leading him to **concede** defeat.                                 | "I **concede** that it's *cons'* *seed*, but I need feed!"                                                      |
| conciliatory  | A *con* man helps a wounded *seal* *he* found, *tearing* his clothes for a bandage in a **conciliatory** act, leading to his *re*formation. | The *con's* *silly* *story* - a **conciliatory** gesture.                                                      |
| contend       | The city's *con* artist *tends* to **contend** that he's misunderstood.                                                    | He **contends** that a *con* *tends* to return.                                                                 |
| conventional  | *Con* finds a *van*, and against his **conventional** nature to *shun* *all* rules, reports it.                           | At a *convention*, *all* must wear **conventional** suits.                                                     |
| conviction*   | *Con* artist *Victor*'s **conviction** was proven by the necklace found against his *shin*.                               | "It is my **conviction** that every *convict* should *shun* guns."                                              |
| cordial       | In the city's *core*, the **cordial** shopkeeper makes fair *deals*.                                                      | "I've cut the *cord*, *Jill*!" (Relations are no longer **cordial**.)                                          |
| cryptic       | In the *crypt*, a mysterious '*tick*' sound was a **cryptic** secret.                                                      | A **cryptic** *crypt* *tick*.                                                                                  |
| degradation   | The *degrade* endured by the *Asian* immigrant led to his personal **degradation**.                                        | **Degradation** from a "*D*" *grade* *date* - *shun* it!                                                       |
| depravity     | The *deep*, *rave*-filled *city* hides a world of **depravity**.                                                          | *Deep* in the *rabbit* warren, *he* tells them a tale of **depravity**.                                        |
| deprecate     | Luna looks at the *deep* sea *wreck* with *hate*, **deprecating** man's recklessness.                                     | Near *Deep-Wreck* *8*, they **deprecate** the "Catch of the Day."                                              |
| disputatious  | At "*Dis* Church," the *pew* is filled with **disputatious** locals, until Mrs. *Tat* attempts to *shush* them.           | *Dispute* *8*. *Just* another dispute between **disputatious** dates.                                          |
| divergent*    | The *ant*, on the *verge* of *dying*, faced **divergent** paths.                                                          | *Di* on the *verge* of going with a *gent* on a **divergent** path.                                            |
| egotism       | Mr. *Ego*, over his *tea*, tallies up the *sum* of his achievements, revealing his **egotism**.                           | The main concern of *E* *goat* *is* *himself*. What **egotism**!                                               |
| emulate       | The usually punctual *emu* was *late*, yet other birds still sought to **emulate** its habits.                            | "*Em*, *you're* *late*! Must you **emulate** girls who make their dates wait?"                                |
| enmity        | The *hen* displays her **enmity** towards the farmer's golf *mitt* at the *tee*.                                         | The *N* *mitt* *he* wears causes **enmity**.                                                                   |
| exhaustive    | An *ex*-champion *horse* turned *stiff* from his **exhaustive** training.                                                | "Our **exhaustive** battery of tests does not *exhaust* *Steve*."                                              |
| feasible      | With the rise in *fees*, John was still *able* to pay, making it a **feasible** solution for him.                         | It's not **feasible** to pay *fees* to *a* *bull*.                                                             |
| flagrant      | The king's **flagrant** *flaw* was to *grant* favors indiscriminately, causing outrage.                                  | **Flagrant** hostility at a *flag* *rant*.                                                                     |
| gullible      | The *gull*, by moving his *lip*, convinces the **gullible** *bull* of his stories.                                       | "If you believe in the *gull-a-bull*, you must be **gullible**!"                                               |
| ignominy      | The man with an *egg* has *no* *money*, embodying his **ignominy**.                                                       | *A* *gnome*, *Minnie*, suffers no **ignominy**.                                                                |
| illusory      | *Ill* and fearing he will *lose* everything, John says *sorry* in his **illusory** world.                                | *A* *Lew*, *sorry* for having followed an **illusory** dream.                                                  |
| implement     | An *imp*, after a deep *lament*, decides to **implement** changes to his behavior.                                       | They **implement** a curfew to an *imp* *lament*.                                                              |
| inclusive     | *In* the search for a *clue*, the detective's **inclusive** method acted like a *sieve*, filtering through all the evidence. | Look *in* *clues* *if* you seek **inclusive** evidence.                                                       |
| inconsequential | The artist finds *ink* *on* his *sequence* of strokes but remains *chill*, deeming it **inconsequential**.            | "It's **inconsequential** how we go, but *in* *con* *sequence* *shall* we go if you insist!"                   |
| incorrigible  | The artist used *ink* for his drawing of an *or*-like *ridge* and a *bull*, but the bull was an **incorrigible** mistake. | Trying to *encourage* *a* *bull* to cease his **incorrigible** ways.                                           |
| indifferent   | He was **indifferent**, even *in* a *different* situation.                                                               | People *in* *different* lands being **indifferent** to each other.                                             |
| ingenious     | Dr. Jensen found an **ingenious** solution *in* the *gene*, saying '*yes*' to his eureka moment.                         | *In* *genius* we find **ingenious** ideas.                                                                    |
| intimidate    | "*In* a *tea* gathering, a *mate* walked in to **intimidate** everyone."                                                | An *intimate* *date* tends to **intimidate** her.                                                              |
| intrepid      | *In* his *trip*, the **intrepid** explorer fearlessly faced what *hid* in the shadows.                                  | Even the most **intrepid** explorer should, *in* his *trip*, *heed* warnings.                                  |
| oblivion      | Joe wished, "*Oh*, *live* *beyond* this hardship," but his dreams sank into **oblivion**.                                | *Ob* *lived* and *eon* before Oblantis fell into **oblivion**.                                                |
| opportunist   | Always looking *up* for a *port* of advantage, *you* would see an **opportunist** building his *nest* on others' misfortunes. | At *a* *port* near *Tunis*, an **opportunist** waits.                                                        |
| opulence      | An overwhelmed man exclaims "*Oh!*" as he sits at a *pew*, observing the cathedral's **opulence** through his *lens*.    | "An *opal* *lance*? Such **opulence** in this palace!"                                                         |
| peripheral    | A *pair* teased with 'what *if* *her* *doll* disappears?', hiding it in **peripheral** areas, but her attention captured it all. | "There's a *pear* *for* *all* on the **peripheral** pear trees!"                                           |
| phenomena     | Sarah, studying **phenomena**, was on the *phone* when she had to say, "*No*, *Ma*."                                    | "And now it's a *fin* *omen* - *ahhh*! - rare **phenomena**"                                                  |
| polemical     | The **polemical** John, standing like a *pole*, accuses *me* of having ideas as dark as *coal*.                        | A **polemical** *polar* *Mick* *call*.                                                                       |
| quiescence    | The *key* to peace is in the *essence* of **quiescence**.                                                               | *Qwee* *Essence* brings **quiescence**.                                                                       |
| rant          | She *ran* out of patience waiting for her *tea* and went on a **rant**.                                                 | "By *Ra*, that *ant* can **rant**!"                                                                          |
| ratify        | The *rat* agrees to **ratify** a *tie*-up treaty for a *fee*.                                                           | "I'll be a *rat* *if* *I* **ratify** this treaty."                                                           |
| recount       | Mathematician *Ree* had to *count* and then **recount** to secure her win.                                              | Recounting how *Rick* was picked to *count* the votes in the **recount**.                                     |
| rectify       | Wearing his *red* *tie*, he decided to *fie* and **rectify** his mistake.                                               | "I'll be *wrecked* *if* *I* don't **rectify** my neighbor's behavior."                                       |
| rescind       | The courier had the letter on his *wrist* to *send*, but the order was **rescinded**.                                   | *Reese* *sent* his team a memo to **rescind** his previous one.                                              |
| retract       | After *reading* the clean *track* record of the suspect, the detective had to **retract** his suspicion.                | *Rhet* *tracked* through the woods to **retract** his words.                                                  |
| rigor         | On the *ridge*, John says "*Er*..." but the **rigor** of his training encourages him to continue.                      | The *rig* is checked by captain *Gore* with **rigor**.                                                        |
| stoic         | A fire starts from the *stove*, to which the **stoic** chef merely reacts with '*ick*'.                                 | **Stoic** customers tuck at the *Stowe* *Wick* in Stowe, Vermont.                                             |
| surreptitious | '*Sir*', a '*rep*' manager, needs to hide a scandalous *titbit* with a **surreptitious** '*shush*'.                    | *Sir* *Repetitious* in a **surreptitious** operation.                                                         |
| tantamount    | The *ant* finds a *tea* *mound* **tantamount** to a valuable treasure.                                                 | Using *Tant* as *a* *mount* to ascend El Pico in Peru is **tantamount** to saying alpacas' rights are few!   |
| threadbare    | Worn to a *thread*, the *bear* became **threadbare** but still cherished.                                              | *Thread* *Bear* takes orders from the **threadbare** customers.                                               |
| unwarranted   | An unexpected '*un*' *war* *ran* through *Ted*'s land, leading to his **unwarranted** accusation.                       | "*A* *warrant*?" *Ted* asked. "That's **unwarranted**."                                                      |
| virtuoso      | *Veer*'s talent was *too* remarkable, *so* he became a **virtuoso**.                                                   | This **virtuoso** has a *virtue* *oh* *so* rare - he spreads cheer far and near.                             |

---
