# JavaDateApp

        // First Day & Last Day of Week
        LocalDate.now().with(DayOfWeek.MONDAY).format(DateTimeFormatter.ofPattern("dd/MM/yyyy"));
        LocalDate.now().with(DayOfWeek.SUNDAY).format(DateTimeFormatter.ofPattern("dd/MM/yyyy"));

        // First Day & Last Day of Month
        LocalDate.now().with(TemporalAdjusters.firstInMonth(DayOfWeek.MONDAY)).format(DateTimeFormatter.ofPattern("dd/MM/yyyy"));
        LocalDate.now().with(TemporalAdjusters.lastDayOfMonth()).format(DateTimeFormatter.ofPattern("dd/MM/yyyy"));

        // Start Date & End of Date
        LocalDate.now().with(DayOfWeek.MONDAY).format(DateTimeFormatter.ofPattern("dd/MM/yyyy"));
        LocalDate.now().with(DayOfWeek.SUNDAY).format(DateTimeFormatter.ofPattern("dd/MM/yyyy"));
