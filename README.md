# DSAI-HW3-Addition-Practice
- Use AI to add and subtract
- Generate data that A >= B
- Data generated randomly

## Report
### Training epoch
When we train the data more and more the output becomes accurate.
Once the data reached 90% accuracy the more epoch added may affect the result of RNN
If try to change the epoch to lower than 50, the result is bad and not useful.
The more data generated will improve the to model to be trained better.

### Data size
While increasing the data size, the RNN does get better result.
But after the data size is greater than specific range, it doesn't do any better.
(data coverage should be wide enough)

### Can it apply for multiplication?
No, The data is too complicated for the machine to learn using RNN
because the result of each number is just too big for RNN to learn.
The complexity is too much and just by add and subtract the success guess rate is just around 70%.
RNN can be applied for stocks prediction or something that can be tracked by historical data.
