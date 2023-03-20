# Airdrop Season One

**Airdrop Details**
https://docs.google.com/spreadsheets/d/1v-adBFGal7nPF2YZO2_95srUx4gvGrpvjzPo3J4Jfnk/edit?usp=sharing
<br>
<br>
**Formula**
```math
basePoint=0.12*holdingDays+0.08*min(365 - holdingDays,daystoExpiry)+
```
```math
0.1*max(daysToExpiry+holdingDays-365,0)+
```
```math
max(645*bnb3Character,155*bnb4Character)+max(395*arb3Character,75*arb4Character)+
```
```math
voyage1*5+voyage2*10+voyage3*10+voyage1*voyage2*voyage3*10
```
<br>

```math
booster=1*(2*primaryName)*min(1+(galxeOat*0.01),1.2)*(1.2*HoldingBothBnbArb)
```
<br>

```math
totalPoints = basePoint*booster
```
<br>

```math
baseToken=41,400,000/\sum_{k=1}^n totalPoints
```
<br>

```math
additionalHoldingDaysToken=5,600,000/\sum_{k=1}^n holdingDays
```
<br>

```math
totalToken=baseToken+additionalHoldingDaysToken
```
