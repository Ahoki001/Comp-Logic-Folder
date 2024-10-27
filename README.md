START

    // Initialize variables
    DECLARE totalHoursPerWeek AS INTEGER
    DECLARE totalHoursPerYear AS INTEGER
    DECLARE hoursWorkedPerDay AS INTEGER
    DECLARE daysInWeek AS INTEGER = 5
    DECLARE workdaysInYear AS INTEGER = 252

    // Prompt user for input
    PRINT "Enter the number of hours worked per day:"
    INPUT hoursWorkedPerDay

    // Calculate total hours worked in a week
    totalHoursPerWeek = hoursWorkedPerDay * daysInWeek

    // Calculate total hours worked in a year
    totalHoursPerYear = hoursWorkedPerDay * workdaysInYear

    // Display results
    PRINT "Total hours worked in a week: " + totalHoursPerWeek
    PRINT "Total hours worked in a year: " + totalHoursPerYear

END 
