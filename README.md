# START
    INPUT isMember
    INPUT payment
    IF isMember = TRUE
        INPUT timeYear
        IF timeYear > 5
            IF payment >= 50000
                OUTPUT *15%*
            ELSE
                OUTPUT *10%*
            END IF
        ELSE
            OUTPUT 5%
        END IF
    ELSE
        IF payment >= 20000
            OUTPUT 5%
        ELSE
            OUTPUT 0%
        END IF
    END IF
# END

_TEST_
**TEST**
## TEST

|1|2|
|---|---
|3|4|
