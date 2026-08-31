Initialize demandScore = 0
Input patientVisits, treatmentDemand, facilityUtilization, emergencySurge
For each parameter in (patientVisits, treatmentDemand, facilityUtilization, emergencySurge)
    If parameter > threshold
        Increment demandScore by 1
    Else
        Do nothing
End For
If demandScore >= 3
    Display "High Demand"
Else If demandScore == 2
    Display "Medium Demand"
Else
    Display "Low Demand"
End If
