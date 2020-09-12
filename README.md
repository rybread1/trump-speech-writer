# Create a LSTM model to generate text in a "trumpian" fashion.

Trained on a collection of speeches and interviews from Donald Trump's 2016 Campaign trail.

**An example from the Network:**

>> It is so wonderful to be in this beautiful city, we must also be a safe country. Immigration security is national security. Hillary's pledge to enact "open borders", she means totally unlimited immigration. In fact, Hillary Clinton has terrible instincts on WikiLeaks and deleted and an ally of the United States, plus another $130 billion -- and it's the same attitude of arrogance and entitlement that led her to violate federal law as Secretary of State, hide and delete her emails, destroy her phones with a hammer, to protect those jurisdictions that do assist federal authorities. Number five, cancel unconstitutional executive orders and enforce all laws relating to help and expand its health care costs are numerous to vote for Trump. Early ballots are mailed out on October 12th, and the destruction of our country. I am asking for your vote so we can replace Obamacare and save health care for their families, and yes, we will build a wall. We are the campaign of unity, and we are going to bring our jobs back. Mexico's something nice? I don't think so. I don't think so. She comes home, and he said, outrageously, it's like , it's stampede , "Oh, that's crass." It's just one more reason why, it is going to be a victory for the White House, and we re going to make America great again. Thank you very much, Michigan. It's going to be a victory for the people. We Will Make America Wealthy Again. We Will Make America Strong Again. We Will Make America Safe Again. And We Will Make America Great Again. Thank you, and God Bless!


# TO-DO:
- [x] test next character prediction vs. next word prediction -- next word prediction is more sensible, but it also leads to more predictable outcomes and repeating of actual real text from the speeches. Next character prediction is more non-sensical but is more generative.
- [x] add additional dense layers
- [x] try stacking LSTM layers
- [x] spend additional time during preprocess steps - token splitting logic, etc
