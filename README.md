# User_Analysis
A/B testing on user analysis 

Presentasi : https://docs.google.com/presentation/d/14o4k4msNfr-gjWNzKmRteb0owm4wPFEncPiXQ17s2xc/edit?usp=sharing

Data save as `data` with columns : 
- event_name
- device_id_hash
- event_timestamp
- exp_id
- date

There're 5 type of `event_name` with result :
- `MainScreenAppear` with 119205 or 48.8%
- `OffersScreenAppear` with 46825 or 19.1%
- `CartScreenAppear` with 42731 or 17.5%
- `PaymentScreenSuccessful` with 34313 or 14%
- `Tutorial` with 1052 or 0.4%

There're `7551` users that register on log with average event on `32.33`.

The data we're going to use is from `2019-08-01` with `241298` datas.

Here's the comparison result between the data :
- There're some decrease on `MainScreenAppear` around `-1.48`
- While on `PaymentScreenSuccessful` around `-0.58`
- with average of the decreasement on `-1.03`

Here is the data from `exp_id` :
- `246` with `79425`.
- `247` with `77147`.
- `248` with `84726`.

Here's analysis result of `Frekuensi Event` :
- `MainScreenAppear` with `117431` actions.
- `OffersScreenAppear` with `46350` actions.
- `CartScreenAppear` with `42365` actions.
- `PaymentScreenSuccessful` with `34113` actions.
- `Tutorial` with `1039` actions.

Analysis result of `User dan Event` :
- On event `OffersScreenAppear` there're `7468` actions with characteristic user with 1 times interaction is `2` 
- On event `MainScreenAppear` there're `7428` actions with characteristic user with 1 times interaction is `6`
- On event `CartScreenAppear` there're `6431` actions with characteristic user with 1 times interaction is `43`
- On event `PaymentScreenSuccessful` there're `4349` actions with characteristic user with 1 times interaction is `105`
- On event `Tutorial` there're `542` actions with characteristic user with 1 times interaction is `418`

Here's the funnel order `MainScreenAppear, OffersScreenAppear, CartScreenAppear, Tutorial, PaymentScreenSuccessful`. With ratio result :
- Ratio from `MainScreenAppear and OffersScreenAppear` with `0.005385`.
- Ratio from `OffersScreenAppear and CartScreenAppear` with `-0.138859`.
- Ratio from `CartScreenAppear and Tutorial` with `-0.915721` there're a significant decreasement on users on this part.
- Ratio from `Tutorial and PaymentScreenSuccessful` with `7.023985`.

There're 2 categories of users : 
- `94%` or `6953` users is the one who didnt do all the events. 
- `6%` or `466` users is the one who do all the events.

Here's the grouping result :
- `246` have `79425` users
- `247` have `77147` users
- `248` have `84726` users

Analysis result total users from `246` and `247` :
- With max users on `12381` and `12336` users.
- And minimum users on `10599` and`9949` users.
- As for average users on `11346.42` and `11021` users.

Ratio result between group `246` and `247` :
- On event `CartScreenAppear` there are `18.5%` on `246` as for `247` there are `16.1%`
- On event `MainScreenAppear` there are `47.4%` on `246` as for `247` there are `50.7%`
- On event `OffersScreenAppear` there are `18.5%` on `246` as for `247` there are `19.6%`
- On event `PaymentScreenSuccessful` there are `14.9%` on `246` as for `247` there are `13%`
- On event `Tutorial` there are `0.4%` on `246` as for `247` there are `0.4%`

Analysis result from all the groups :
- `CartScreenAppear` result from `248` is between `246` and `247` with result on `17.93%`
- `MainScreenAppear` result from `248` is between `246` and `247` with result on `47.91%`
- `OffersScreenAppear` result from `248` is between `246` and `247` with result on `19.35%`
- `PaymentScreenSuccessful` result from `248` is between `246` and `247` with result on `14.35%`
- `Tutorial` result from `248` is between `246` and `247` with result on `0.44%`
