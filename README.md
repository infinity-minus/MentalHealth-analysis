## MentalHealth-analysis
# This is an Excel dashboard that analyses the Anxiety, Depression and Stress levels in an individual.

Source of the dataset: https://www.kaggle.com/yamqwe/depression-anxiety-stress-scales
This data was collected with an on-line version of the Depression Anxiety Stress Scales (DASS). It was collected between 2017 – 2019.

METADATA:
The following items were included in the survey:
Q1: I found myself getting upset by quite trivial things.
Q2: I was aware of dryness of my mouth.
Q3: I couldn't seem to experience any positive feeling at all.
Q4: I experienced breathing difficulty (eg, excessively rapid breathing, breathlessness in the absence of physical exertion).
Q5: I just couldn't seem to get going.
Q6: I tended to over-react to situations.
Q7: I had a feeling of shakiness (eg, legs going to give way).
Q8: I found it difficult to relax.
Q9: I found myself in situations that made me so anxious I was most relieved when they ended.
Q10: I felt that I had nothing to look forward to.
Q11: I found myself getting upset rather easily.
Q12: I felt that I was using a lot of nervous energy.
Q13: I felt sad and depressed.
Q14: I found myself getting impatient when I was delayed in any way (eg, elevators, traffic lights, being kept waiting).
Q15: I had a feeling of faintness.
Q16: I felt that I had lost interest in just about everything.
Q17: I felt I wasn't worth much as a person.
Q18: I felt that I was rather touchy.
Q19: I perspired noticeably (eg, hands sweaty) in the absence of high temperatures or physical exertion.
Q20: I felt scared without any good reason.
Q21: I felt that life wasn't worthwhile.
Q22: I found it hard to wind down.
Q23: I had difficulty in swallowing.
Q24: I couldn't seem to get any enjoyment out of the things I did.
Q25: I was aware of the action of my heart in the absence of physical exertion (eg, sense of heart rate increase, heart missing a beat).
Q26: I felt down-hearted and blue.
Q27: I found that I was very irritable.
Q28: I felt I was close to panic.
Q29: I found it hard to calm down after something upset me.
Q30: I feared that I would be "thrown" by some trivial but unfamiliar task.
Q31: I was unable to become enthusiastic about anything.
Q32: I found it difficult to tolerate interruptions to what I was doing.
Q33: I was in a state of nervous tension.
Q34: I felt I was pretty worthless.
Q35: I was intolerant of anything that kept me from getting on with what I was doing.
Q36: I felt terrified.
Q37: I could see nothing in the future to be hopeful about.
Q38: I felt that life was meaningless.
Q39: I found myself getting agitated.
Q40: I was worried about situations in which I might panic and make a fool of myself.


Each item was presented one at a time in a random order for each new participant along with a 4 point rating scale asking the user to indicate how often that had been true of them in the past week where

1 = Did not apply to me at all
2 = Applied to me to some degree, or some of the time
3 = Applied to me to a considerable degree, or a good part of the time
4 = Applied to me very much, or most of the time

This response is stored in columns named Q1, Q2, Q3,…

A bunch more questions were then asked:

Education: "How much education have you completed?" 
1=Less than high school, 2=High school, 3=University degree, 4=Graduate degree

Urban: "What type of area did you live when you were a child?" 
1=Rural (country side), 2=Suburban, 3=Urban (town, city)

Gender: "What is your gender?" 
1=Male, 2=Female, 3=Other

Engnat: "Is English your native language?" 
1=Yes, 2=No

Age: "How many years old are you?"

Hand: "What hand do you use to write with?" 
1=Right, 2=Left, 3=Both

Religion: "What is your religion?", 
1=Agnostic, 2=Atheist, 3=Buddhist, 4=Christian (Catholic), 5=Christian (Mormon), 6=Christian (Protestant), 7=Christian (Other), 8=Hindu, 9=Jewish, 10=Muslim, 11=Sikh, 12=Other

Orientation: "What is your sexual orientation?" 
1=Heterosexual, 2=Bisexual, 3=Homosexual, 4=Asexual, 5=Other

Race: "What is your race?"
10=Asian, 20=Arab, 30=Black, 40=Indigenous Australian, 50=Native American, 60=White, 70=Other

Voted: "Have you voted in a national election in the past year?" 
1=Yes, 2=No

Married: "What is your marital status?"
1=Never married, 2=Currently married, 3=Previously married

Familysize: "Including you, how many children did your mother have?"

Major: "If you attended a university, what was your major (e.g. "psychology", "English", "civil engineering")?"

The following values were derived from technical information:
country ISO country code of where the user connected from
screensize: 1=device with small screen (phone, etc), 2=device with big screen (laptop, desktop, etc)
uniquenetworklocation: 1=only one survey from user's specific network in dataset, 2=multiple surveys submitted from the network of this user
