=========
Functions
=========

Spreadsheet functions are divided in the following categories:

- :ref:`Database <functions/database>`
- :ref:`Date <functions/date>`
- :ref:`Engineering <functions/engineering>`
- :ref:`Financial <functions/financial>`
- :ref:`Info <functions/info>`
- :ref:`Lookup <functions/lookup>`
- :ref:`Logical <functions/logical>`
- :ref:`Math <functions/math>`
- :ref:`Misc <functions/misc>`
- :ref:`Odoo <functions/odoo>`
- :ref:`Operators <functions/operators>`
- :ref:`Statistical <functions/statistical>`
- :ref:`Text <functions/text>`

.. _functions/database:

Database
========

.. list-table::
   :header-rows: 1
   :stub-columns: 1

   * - Name and arguments
     - Description or link
   * - DAVERAGE(database, field, criteria)
     - `Excel DAVERAGE article <https://support.microsoft.com/office/daverage-function-a6a2d5ac-4b4b-48cd-a1d8-7b37834e5aee>`_
   * - DCOUNT(database, field, criteria)
     - `Excel DCOUNT article <https://support.microsoft.com/office/dcount-function-c1fc7b93-fb0d-4d8d-97db-8d5f076eaeb1>`_
   * - DCOUNTA(database, field, criteria)
     - `Excel DCOUNTA article <https://support.microsoft.com/office/dcounta-function-00232a6d-5a66-4a01-a25b-c1653fda1244>`_
   * - DGET(database, field, criteria)
     - `Excel DGET article <https://support.microsoft.com/office/dget-function-455568bf-4eef-45f7-90f0-ec250d00892e>`_
   * - DMAX(database, field, criteria)
     - `Excel DMAX article <https://support.microsoft.com/office/dmax-function-f4e8209d-8958-4c3d-a1ee-6351665d41c2>`_
   * - DMIN(database, field, criteria)
     - `Excel DMIN article <https://support.microsoft.com/office/dmin-function-4ae6f1d9-1f26-40f1-a783-6dc3680192a3>`_
   * - DPRODUCT(database, field, criteria)
     - `Excel DPRODUCT article <https://support.microsoft.com/office/dproduct-function-4f96b13e-d49c-47a7-b769-22f6d017cb31>`_
   * - DSTDEV(database, field, criteria)
     - `Excel DSTDEV article <https://support.microsoft.com/office/dstdev-function-026b8c73-616d-4b5e-b072-241871c4ab96>`_
   * - DSTDEVP(database, field, criteria)
     - `Excel DSTDEVP article <https://support.microsoft.com/office/dstdevp-function-04b78995-da03-4813-bbd9-d74fd0f5d94b>`_
   * - DSUM(database, field, criteria)
     - `Excel DSUM article <https://support.microsoft.com/office/dsum-function-53181285-0c4b-4f5a-aaa3-529a322be41b>`_
   * - DVAR(database, field, criteria)
     - `Excel DVAR article <https://support.microsoft.com/office/dvar-function-d6747ca9-99c7-48bb-996e-9d7af00f3ed1>`_
   * - DVARP(database, field, criteria)
     - `Excel DVARP article <https://support.microsoft.com/office/dvarp-function-eb0ba387-9cb7-45c8-81e9-0394912502fc>`_

.. _functions/date:

Date
====

.. list-table::
   :header-rows: 1
   :stub-columns: 1

   * - Name and arguments
     - Description or link
   * - DATE(year, month, day)
     - `Excel DATE article <https://support.microsoft.com/office/date-function-e36c0c8c-4104-49da-ab83-82328b832349>`_
   * - DATEVALUE(date_string)
     - `Excel DATEVALUE article <https://support.microsoft.com/office/datevalue-function-df8b07d4-7761-4a93-bc33-b7471bbff252>`_
   * - DAY(date)
     - `Excel DAY article <https://support.microsoft.com/office/day-function-8a7d1cbb-6c7d-4ba1-8aea-25c134d03101>`_
   * - DAYS(end_date, start_date)
     - `Excel DAYS article <https://support.microsoft.com/office/days-function-57740535-d549-4395-8728-0f07bff0b9df>`_
   * - DAYS360(start_date, end_date, [method])
     - `Excel DAYS360 article <https://support.microsoft.com/office/days360-function-b9a509fd-49ef-407e-94df-0cbda5718c2a>`_
   * - EDATE(start_date, months)
     - `Excel EDATE article <https://support.microsoft.com/office/edate-function-3c920eb2-6e66-44e7-a1f5-753ae47ee4f5>`_
   * - EOMONTH(start_date, months)
     - `Excel EOMONTH article <https://support.microsoft.com/office/eomonth-function-7314ffa1-2bc9-4005-9d66-f49db127d628>`_
   * - HOUR(time)
     - `Excel HOUR article <https://support.microsoft.com/office/hour-function-a3afa879-86cb-4339-b1b5-2dd2d7310ac7>`_
   * - ISOWEEKNUM(date)
     - `Excel ISOWEEKNUM article <https://support.microsoft.com/office/isoweeknum-function-1c2d0afe-d25b-4ab1-8894-8d0520e90e0e>`_
   * - MINUTE(time)
     - `Excel MINUTE article <https://support.microsoft.com/office/minute-function-af728df0-05c4-4b07-9eed-a84801a60589>`_
   * - MONTH(date)
     - `Excel MONTH article <https://support.microsoft.com/office/month-function-579a2881-199b-48b2-ab90-ddba0eba86e8>`_
   * - NETWORKDAYS(start_date, end_date, [holidays])
     - `Excel NETWORKDAYS article <https://support.microsoft.com/office/networkdays-function-48e717bf-a7a3-495f-969e-5005e3eb18e7>`_
   * - NETWORKDAYS.INTL(start_date, end_date, [weekend], [holidays])
     - `Excel NETWORKDAYS.INTL article <https://support.microsoft.com/office/networkdays-intl-function-a9b26239-4f20-46a1-9ab8-4e925bfd5e28>`_
   * - NOW()
     - `Excel NOW article <https://support.microsoft.com/office/now-function-3337fd29-145a-4347-b2e6-20c904739c46>`_
   * - SECOND(time)
     - `Excel SECOND article <https://support.microsoft.com/office/second-function-740d1cfc-553c-4099-b668-80eaa24e8af1>`_
   * - TIME(hour, minute, second)
     - `Excel TIME article <https://support.microsoft.com/office/time-function-9a5aff99-8f7d-4611-845e-747d0b8d5457>`_
   * - TIMEVALUE(time_string)
     - `Excel TIMEVALUE article <https://support.microsoft.com/office/timevalue-function-0b615c12-33d8-4431-bf3d-f3eb6d186645>`_
   * - TODAY()
     - `Excel TODAY article <https://support.microsoft.com/office/today-function-5eb3078d-a82c-4736-8930-2f51a028fdd9>`_
   * - WEEKDAY(date, [type])
     - `Excel WEEKDAY article <https://support.microsoft.com/office/weekday-function-60e44483-2ed1-439f-8bd0-e404c190949a>`_
   * - WEEKNUM(date, [type])
     - `Excel WEEKNUM article <https://support.microsoft.com/office/weeknum-function-e5c43a03-b4ab-426c-b411-b18c13c75340>`_
   * - WORKDAY(start_date, num_days, [holidays])
     - `Excel WORKDAY article <https://support.microsoft.com/office/workday-function-f764a5b7-05fc-4494-9486-60d494efbf33>`_
   * - WORKDAY.INTL(start_date, num_days, [weekend], [holidays])
     - `Excel WORKDAY.INTL article <https://support.microsoft.com/office/workday-intl-function-a378391c-9ba7-4678-8a39-39611a9bf81d>`_
   * - YEAR(date)
     - `Excel YEAR article <https://support.microsoft.com/office/year-function-c64f017a-1354-490d-981f-578e8ec8d3b9>`_
   * - YEARFRAC(start_date, end_date, [day_count_convention])
     - Exact number of years between two dates (not compatible with Excel)
   * - MONTH.START(date)
     - First day of the month preceding a date (not compatible with Excel)
   * - MONTH.END(date)
     - Last day of the month following a date (not compatible with Excel)
   * - QUARTER(date)
     - Quarter of the year a specific date falls in (not compatible with Excel)
   * - QUARTER.START(date)
     - First day of the quarter of the year a specific date falls in (not compatible with Excel)
   * - QUARTER.END(date)
     - Last day of the quarter of the year a specific date falls in (not compatible with Excel)
   * - YEAR.START(date)
     - First day of the year a specific date falls in (not compatible with Excel)
   * - YEAR.END(date)
     - Last day of the year a specific date falls in (not compatible with Excel)

.. _functions/engineering:

Engineering
===========

.. list-table::
   :header-rows: 1
   :stub-columns: 1

   * - Name and arguments
     - Description or link
   * - DELTA(number1, [number2])
     - `Excel DELTA article <https://support.microsoft.com/en-us/office/delta-function-2f763672-c959-4e07-ac33-fe03220ba432>`_

.. _functions/financial:

Financial
=========

.. list-table::
   :header-rows: 1
   :stub-columns: 1

   * - Name and arguments
     - Description or link
   * - ACCRINTM(issue, maturity, rate, redemption, [day_count_convention])
     - `Excel ACCRINTM article <>`_
   * - AMORLINC(cost, purchase_date, first_period_end, salvage, period, rate, [day_count_convention])
     - `Excel AMORLINC article <>`_
   * - COUPDAYS(settlement, maturity, frequency, [day_count_convention])
     - `Excel COUPDAYS article <>`_
   * - COUPDAYBS(settlement, maturity, frequency, [day_count_convention])
     - `Excel COUPDAYBS article <>`_
   * - COUPDAYSNC(settlement, maturity, frequency, [day_count_convention])
     - `Excel COUPDAYSNC article <>`_
   * - COUPNCD(settlement, maturity, frequency, [day_count_convention])
     - `Excel COUPNCD article <>`_
   * - COUPNUM(settlement, maturity, frequency, [day_count_convention])
     - `Excel COUPNUM article <>`_
   * - COUPPCD(settlement, maturity, frequency, [day_count_convention])
     - `Excel COUPPCD article <>`_
   * - CUMIPMT(rate, number_of_periods, present_value, first_period, last_period, [end_or_beginning])
     - `Excel CUMIPMT article <>`_
   * - CUMPRINC(rate, number_of_periods, present_value, first_period, last_period, [end_or_beginning])
     - `Excel CUMPRINC article <>`_
   * - DB(cost, salvage, life, period, [month])
     - `Excel DB article <>`_
   * - DDB(cost, salvage, life, period, [factor])
     - `Excel DDB article <>`_
   * - DISC(settlement, maturity, price, redemption, [day_count_convention])
     - `Excel DISC article <>`_
   * - DOLLARDE(fractional_price, unit)
     - `Excel DOLLARDE article <>`_
   * - DOLLARFR(decimal_price, unit)
     - `Excel DOLLARFR article <>`_
   * - DURATION(settlement, maturity, rate, yield, frequency, [day_count_convention])
     - `Excel DURATION article <>`_
   * - EFFECT(nominal_rate, periods_per_year)
     - `Excel EFFECT article <>`_
   * - FV(rate, number_of_periods, payment_amount, [present_value], [end_or_beginning])
     - `Excel FV article <>`_
   * - FVSCHEDULE(principal, rate_schedule)
     - `Excel FVSCHEDULE article <>`_
   * - INTRATE(settlement, maturity, investment, redemption, [day_count_convention])
     - `Excel INTRATE article <>`_
   * - IPMT(rate, period, number_of_periods, present_value, [future_value], [end_or_beginning])
     - `Excel IPMT article <>`_
   * - IRR(cashflow_amounts, [rate_guess])
     - `Excel IRR article <>`_
   * - ISPMT(rate, period, number_of_periods, present_value)
     - `Excel ISPMT article <>`_
   * - MDURATION(settlement, maturity, rate, yield, frequency, [day_count_convention])
     - `Excel MDURATION article <>`_
   * - MIRR(cashflow_amounts, financing_rate, reinvestment_return_rate)
     - `Excel MIRR article <>`_
   * - NOMINAL(effective_rate, periods_per_year)
     - `Excel NOMINAL article <>`_
   * - NPER(rate, payment_amount, present_value, [future_value], [end_or_beginning])
     - `Excel NPER article <>`_
   * - NPV(discount, cashflow1, [cashflow2, ...])
     - `Excel NPV article <>`_
   * - PDURATION(rate, present_value, future_value)
     - `Excel PDURATION article <>`_
   * - PMT(rate, number_of_periods, present_value, [future_value], [end_or_beginning])
     - `Excel PMT article <>`_
   * - PPMT(rate, period, number_of_periods, present_value, [future_value], [end_or_beginning])
     - `Excel PPMT article <>`_
   * - PV(rate, number_of_periods, payment_amount, [future_value], [end_or_beginning])
     - `Excel PV article <>`_
   * - PRICE(settlement, maturity, rate, yield, redemption, frequency, [day_count_convention])
     - `Excel PRICE article <>`_
   * - PRICEDISC(settlement, maturity, discount, redemption, [day_count_convention])
     - `Excel PRICEDISC article <>`_
   * - PRICEMAT(settlement, maturity, issue, rate, yield, [day_count_convention])
     - `Excel PRICEMAT article <>`_
   * - RATE(number_of_periods, payment_per_period, present_value, [future_value], [end_or_beginning], [rate_guess])
     - `Excel RATE article <>`_
   * - RECEIVED(settlement, maturity, investment, discount, [day_count_convention])
     - `Excel RECEIVED article <>`_
   * - RRI(number_of_periods, present_value, future_value)
     - `Excel RRI article <>`_
   * - SLN(cost, salvage, life)
     - `Excel SLN article <>`_
   * - SYD(cost, salvage, life, period)
     - `Excel SYD article <>`_
   * - TBILLPRICE(settlement, maturity, discount)
     - `Excel TBILLPRICE article <>`_
   * - TBILLEQ(settlement, maturity, discount)
     - `Excel TBILLEQ article <>`_
   * - TBILLYIELD(settlement, maturity, price)
     - `Excel TBILLYIELD article <>`_
   * - VDB(cost, salvage, life, start, end, [factor], [no_switch])
     - `Excel VDB article <>`_
   * - XIRR(cashflow_amounts, cashflow_dates, [rate_guess])
     - `Excel XIRR article <>`_
   * - XNPV(discount, cashflow_amounts, cashflow_dates)
     - `Excel XNPV article <>`_
   * - YIELD(settlement, maturity, rate, price, redemption, frequency, [day_count_convention])
     - `Excel YIELD article <>`_
   * - YIELDDISC(settlement, maturity, price, redemption, [day_count_convention])
     - `Excel YIELDDISC article <>`_
   * - YIELDMAT(settlement, maturity, issue, rate, price, [day_count_convention])
     - `Excel YIELDMAT article <>`_

.. _functions/info:

Info
====

.. list-table::
   :header-rows: 1
   :stub-columns: 1

   * - Name and arguments
     - Description or link
   * - ISERR(value)
     - `Excel ISERR article <>`_
   * - ISERROR(value)
     - `Excel ISERROR article <>`_
   * - ISLOGICAL(value)
     - `Excel ISLOGICAL article <>`_
   * - ISNA(value)
     - `Excel ISNA article <>`_
   * - ISNONTEXT(value)
     - `Excel ISNONTEXT article <>`_
   * - ISNUMBER(value)
     - `Excel ISNUMBER article <>`_
   * - ISTEXT(value)
     - `Excel ISTEXT article <>`_
   * - ISBLANK(value)
     - `Excel ISBLANK article <>`_
   * - NA()
     - `Excel NA article <>`_

.. _functions/lookup:

Lookup
======

.. list-table::
   :header-rows: 1
   :stub-columns: 1

   * - Name and arguments
     - Description or link
   * - COLUMN([cell_reference])
     - `Excel COLUMN article <>`_
   * - COLUMNS(range)
     - `Excel COLUMNS article <>`_
   * - HLOOKUP(search_key, range, index, [is_sorted])
     - `Excel HLOOKUP article <>`_
   * - INDEX(reference, row, column)
     - `Excel INDEX article <>`_
   * - LOOKUP(search_key, search_array, [result_range])
     - `Excel LOOKUP article <>`_
   * - MATCH(search_key, range, [search_type])
     - `Excel MATCH article <>`_
   * - ROW([cell_reference])
     - `Excel ROW article <>`_
   * - ROWS(range)
     - `Excel ROWS article <>`_
   * - VLOOKUP(search_key, range, index, [is_sorted])
     - `Excel VLOOKUP article <>`_
   * - XLOOKUP(search_key, lookup_range, return_range, [if_not_found], [match_mode], [search_mode])
     - `Excel XLOOKUP article <>`_

.. _functions/logical:

Logical
=======

.. list-table::
   :header-rows: 1
   :stub-columns: 1

   * - Name and arguments
     - Description or link
   * - AND(logical_expression1, [logical_expression2, ...])
     - `Excel AND article <>`_
   * - IF(logical_expression, value_if_true, [value_if_false])
     - `Excel IF article <>`_
   * - IFERROR(value, [value_if_error])
     - `Excel IFERROR article <>`_
   * - IFNA(value, [value_if_error])
     - `Excel IFNA article <>`_
   * - IFS(condition1, value1, [condition2, ...], [value2, ...])
     - `Excel IFS article <>`_
   * - NOT(logical_expression)
     - `Excel NOT article <>`_
   * - OR(logical_expression1, [logical_expression2, ...])
     - `Excel OR article <>`_
   * - XOR(logical_expression1, [logical_expression2, ...])
     - `Excel XOR article <>`_

.. _functions/math:

Math
====

.. list-table::
   :header-rows: 1
   :stub-columns: 1

   * - Name and arguments
     - Description or link
   * - ABS(value)
     - `Excel ABS article <>`_
   * - ACOS(value)
     - `Excel ACOS article <>`_
   * - ACOSH(value)
     - `Excel ACOSH article <>`_
   * - ACOT(value)
     - `Excel ACOT article <>`_
   * - ACOTH(value)
     - `Excel ACOTH article <>`_
   * - ASIN(value)
     - `Excel ASIN article <>`_
   * - ASINH(value)
     - `Excel ASINH article <>`_
   * - ATAN(value)
     - `Excel ATAN article <>`_
   * - ATAN2(x, y)
     - `Excel ATAN2 article <>`_
   * - ATANH(value)
     - `Excel ATANH article <>`_
   * - CEILING(value, [factor])
     - `Excel CEILING article <>`_
   * - CEILING.MATH(number, [significance], [mode])
     - `Excel CEILING.MATH article <>`_
   * - CEILING.PRECISE(number, [significance])
     - `Excel CEILING.PRECISE article <>`_
   * - COS(angle)
     - `Excel COS article <>`_
   * - COSH(value)
     - `Excel COSH article <>`_
   * - COT(angle)
     - `Excel COT article <>`_
   * - COTH(value)
     - `Excel COTH article <>`_
   * - COUNTBLANK(value1, [value2, ...])
     - `Excel COUNTBLANK article <>`_
   * - COUNTIF(range, criterion)
     - `Excel COUNTIF article <>`_
   * - COUNTIFS(criteria_range1, criterion1, [criteria_range2, ...], [criterion2, ...])
     - `Excel COUNTIFS article <>`_
   * - COUNTUNIQUE(value1, [value2, ...])
     - Counts number of unique values in a range.
   * - COUNTUNIQUEIFS(range, criteria_range1, criterion1, [criteria_range2, ...], [criterion2, ...])
     - Counts number of unique values in a range, filtered by a set of criteria.
   * - CSC(angle)
     - `Excel CSC article <>`_
   * - CSCH(value)
     - `Excel CSCH article <>`_
   * - DECIMAL(value, base)
     - `Excel DECIMAL article <>`_
   * - DEGREES(angle)
     - `Excel DEGREES article <>`_
   * - EXP(value)
     - `Excel EXP article <>`_
   * - FLOOR(value, [factor])
     - `Excel FLOOR article <>`_
   * - FLOOR.MATH(number, [significance], [mode])
     - `Excel FLOOR.MATH article <>`_
   * - FLOOR.PRECISE(number, [significance])
     - `Excel FLOOR.PRECISE article <>`_
   * - ISEVEN(value)
     - `Excel ISEVEN article <>`_
   * - ISO.CEILING(number, [significance])
     - `Excel ISO.CEILING article <>`_
   * - ISODD(value)
     - `Excel ISODD article <>`_
   * - LN(value)
     - `Excel LN article <>`_
   * - MOD(dividend, divisor)
     - `Excel MOD article <>`_
   * - ODD(value)
     - `Excel ODD article <>`_
   * - PI()
     - `Excel PI article <>`_
   * - POWER(base, exponent)
     - `Excel POWER article <>`_
   * - PRODUCT(factor1, [factor2, ...])
     - `Excel PRODUCT article <>`_
   * - RAND()
     - `Excel RAND article <>`_
   * - RANDBETWEEN(low, high)
     - `Excel RANDBETWEEN article <>`_
   * - ROUND(value, [places])
     - `Excel ROUND article <>`_
   * - ROUNDDOWN(value, [places])
     - `Excel ROUNDDOWN article <>`_
   * - ROUNDUP(value, [places])
     - `Excel ROUNDUP article <>`_
   * - SEC(angle)
     - `Excel SEC article <>`_
   * - SECH(value)
     - `Excel SECH article <>`_
   * - SIN(angle)
     - `Excel SIN article <>`_
   * - SINH(value)
     - `Excel SINH article <>`_
   * - SQRT(value)
     - `Excel SQRT article <>`_
   * - SUM(value1, [value2, ...])
     - `Excel SUM article <>`_
   * - SUMIF(criteria_range, criterion, [sum_range])
     - `Excel SUMIF article <>`_
   * - SUMIFS(sum_range, criteria_range1, criterion1, [criteria_range2, ...], [criterion2, ...])
     - `Excel SUMIFS article <>`_
   * - TAN(angle)
     - `Excel TAN article <>`_
   * - TANH(value)
     - `Excel TANH article <>`_
   * - TRUNC(value, [places])
     - `Excel TRUNC article <>`_

.. _functions/misc:

Misc
====

.. list-table::
   :header-rows: 1
   :stub-columns: 1

   * - Name and arguments
     - Description or link
   * - FORMAT.LARGE.NUMBER(value, [unit])
     - Apply a large number format

.. _functions/odoo:

Odoo
====

.. list-table::
   :header-rows: 1
   :stub-columns: 1

   * - Name and arguments
     - Description or link
   * - ODOO.CREDIT(account_codes, date_range, [offset], [company_id], [include_unposted])
     - Get the total credit for the specified account(s) and period.
   * - ODOO.DEBIT(account_codes, date_range, [offset], [company_id], [include_unposted])
     - Get the total debit for the specified account(s) and period.
   * - ODOO.BALANCE(account_codes, date_range, [offset], [company_id], [include_unposted])
     - Get the total balance for the specified account(s) and period.
   * - ODOO.FISCALYEAR.START(day, [company_id])
     - Returns the starting date of the fiscal year encompassing the provided date.
   * - ODOO.FISCALYEAR.END(day, [company_id])
     - Returns the ending date of the fiscal year encompassing the provided date.
   * - ODOO.ACCOUNT.GROUP(type)
     - Returns the account ids of a given group.
   * - ODOO.CURRENCY.RATE(currency_from, currency_to, [date])
     - This function takes in two currency codes as arguments, and returns the exchange rate from the first currency to the second as float.
   * - ODOO.LIST(list_id, index, field_name)
     - Get the value from a list.
   * - ODOO.LIST.HEADER(list_id, field_name)
     - Get the header of a list.
   * - _T(value)
     - Get the translated value of the given string
   * - ODOO.FILTER.VALUE(filter_name)
     - Return the current value of a spreadsheet filter.
   * - ODOO.PIVOT(pivot_id, measure_name, [domain_field_name, ...], [domain_value, ...])
     - Get the value from a pivot.
   * - ODOO.PIVOT.HEADER(pivot_id, [domain_field_name, ...], [domain_value, ...])
     - Get the header of a pivot.
   * - ODOO.PIVOT.POSITION(pivot_id, field_name, position)
     - Get the absolute ID of an element in the pivot

.. _functions/operators:

Operators
=========

.. list-table::
   :header-rows: 1
   :stub-columns: 1

   * - Name and arguments
     - Description or link
   * - ADD(value1, value2)
     - Sum of two numbers.
   * - CONCAT(value1, value2)
     - Consult Excel documentation
   * - DIVIDE(dividend, divisor)
     - One number divided by another.
   * - EQ(value1, value2)
     - Equal.
   * - GT(value1, value2)
     - Strictly greater than.
   * - GTE(value1, value2)
     - Greater than or equal to.
   * - LT(value1, value2)
     - Less than.
   * - LTE(value1, value2)
     - Less than or equal to.
   * - MINUS(value1, value2)
     - Difference of two numbers.
   * - MULTIPLY(factor1, factor2)
     - Product of two numbers
   * - NE(value1, value2)
     - Not equal.
   * - POW(base, exponent)
     - A number raised to a power.
   * - UMINUS(value)
     - A number with the sign reversed.
   * - UNARY.PERCENT(percentage)
     - Value interpreted as a percentage.
   * - UPLUS(value)
     - A specified number, unchanged.

.. _functions/statistical:

Statistical
===========

.. list-table::
   :header-rows: 1
   :stub-columns: 1

   * - Name and arguments
     - Description or link
   * - AVEDEV(value1, [value2, ...])
     - `Excel AVEDEV article <>`_
   * - AVERAGE(value1, [value2, ...])
     - `Excel AVERAGE article <>`_
   * - AVERAGE.WEIGHTED(values, weights, [additional_values, ...], [additional_weights, ...])
     - Weighted average.
   * - AVERAGEA(value1, [value2, ...])
     - `Excel AVERAGEA article <>`_
   * - AVERAGEIF(criteria_range, criterion, [average_range])
     - `Excel AVERAGEIF article <>`_
   * - AVERAGEIFS(average_range, criteria_range1, criterion1, [criteria_range2, ...], [criterion2, ...])
     - `Excel AVERAGEIFS article <>`_
   * - COUNT(value1, [value2, ...])
     - `Excel COUNT article <>`_
   * - COUNTA(value1, [value2, ...])
     - `Excel COUNTA article <>`_
   * - COVAR(data_y, data_x)
     - `Excel COVAR article <>`_
   * - COVARIANCE.P(data_y, data_x)
     - `Excel COVARIANCE.P article <>`_
   * - COVARIANCE.S(data_y, data_x)
     - `Excel COVARIANCE.S article <>`_
   * - LARGE(data, n)
     - `Excel LARGE article <>`_
   * - MAX(value1, [value2, ...])
     - `Excel MAX article <>`_
   * - MAXA(value1, [value2, ...])
     - `Excel MAXA article <>`_
   * - MAXIFS(range, criteria_range1, criterion1, [criteria_range2, ...], [criterion2, ...])
     - `Excel MAXIFS article <>`_
   * - MEDIAN(value1, [value2, ...])
     - `Excel MEDIAN article <>`_
   * - MIN(value1, [value2, ...])
     - `Excel MIN article <>`_
   * - MINA(value1, [value2, ...])
     - `Excel MINA article <>`_
   * - MINIFS(range, criteria_range1, criterion1, [criteria_range2, ...], [criterion2, ...])
     - `Excel MINIFS article <>`_
   * - PERCENTILE(data, percentile)
     - `Excel PERCENTILE article <>`_
   * - PERCENTILE.EXC(data, percentile)
     - `Excel PERCENTILE.EXC article <>`_
   * - PERCENTILE.INC(data, percentile)
     - `Excel PERCENTILE.INC article <>`_
   * - QUARTILE(data, quartile_number)
     - `Excel QUARTILE article <>`_
   * - QUARTILE.EXC(data, quartile_number)
     - `Excel QUARTILE.EXC article <>`_
   * - QUARTILE.INC(data, quartile_number)
     - `Excel QUARTILE.INC article <>`_
   * - SMALL(data, n)
     - `Excel SMALL article <>`_
   * - STDEV(value1, [value2, ...])
     - `Excel STDEV article <>`_
   * - STDEV.P(value1, [value2, ...])
     - `Excel STDEV.P article <>`_
   * - STDEV.S(value1, [value2, ...])
     - `Excel STDEV.S article <>`_
   * - STDEVA(value1, [value2, ...])
     - `Excel STDEVA article <>`_
   * - STDEVP(value1, [value2, ...])
     - `Excel STDEVP article <>`_
   * - STDEVPA(value1, [value2, ...])
     - `Excel STDEVPA article <>`_
   * - VAR(value1, [value2, ...])
     - `Excel VAR article <>`_
   * - VAR.P(value1, [value2, ...])
     - `Excel VAR.P article <>`_
   * - VAR.S(value1, [value2, ...])
     - `Excel VAR.S article <>`_
   * - VARA(value1, [value2, ...])
     - `Excel VARA article <>`_
   * - VARP(value1, [value2, ...])
     - `Excel VARP article <>`_
   * - VARPA(value1, [value2, ...])
     - `Excel VARPA article <>`_

.. _functions/text:

Text
====

.. list-table::
   :header-rows: 1
   :stub-columns: 1

   * - Name and arguments
     - Description or link
   * - CHAR(table_number)
     - `Excel CHAR article <>`_
   * - CLEAN(text)
     - `Excel CLEAN article <>`_
   * - CONCATENATE(string1, [string2, ...])
     - `Excel CONCATENATE article <>`_
   * - EXACT(string1, string2)
     - `Excel EXACT article <>`_
   * - FIND(search_for, text_to_search, [starting_at])
     - `Excel FIND article <>`_
   * - JOIN(delimiter, value_or_array1, [value_or_array2, ...])
     - Concatenates elements of arrays with delimiter.
   * - LEFT(text, [number_of_characters])
     - `Excel LEFT article <>`_
   * - LEN(text)
     - `Excel LEN article <>`_
   * - LOWER(text)
     - `Excel LOWER article <>`_
   * - MID(text, starting_at, extract_length)
     - `Excel MID article <>`_
   * - PROPER(text_to_capitalize)
     - `Excel PROPER article <>`_
   * - REPLACE(text, position, length, new_text)
     - `Excel REPLACE article <>`_
   * - RIGHT(text, [number_of_characters])
     - `Excel RIGHT article <>`_
   * - SEARCH(search_for, text_to_search, [starting_at])
     - `Excel SEARCH article <>`_
   * - SUBSTITUTE(text_to_search, search_for, replace_with, [occurrence_number])
     - `Excel SUBSTITUTE article <>`_
   * - TEXTJOIN(delimiter, ignore_empty, text1, [text2, ...])
     - `Excel TEXTJOIN article <>`_
   * - TRIM(text)
     - `Excel TRIM article <>`_
   * - UPPER(text)
     - `Excel UPPER article <>`_
   * - TEXT(number, format)
     - `Excel TEXT article <>`_
