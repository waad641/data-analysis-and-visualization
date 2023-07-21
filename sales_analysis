# Load required libraries
library(ggplot2)

# Read data from CSV file
data <- read.csv("data.csv")

# Calculate mean and total sales
mean_sales <- mean(data$Sales)
total_sales <- sum(data$Sales)

# Print statistics
cat("Mean Sales:", mean_sales, "\n")
cat("Total Sales:", total_sales, "\n")

# Create a line plot to visualize sales trend
ggplot(data, aes(x = Year, y = Sales)) +
  geom_line() +
  geom_point() +
  labs(title = "Yearly Sales Trend",
       x = "Year",
       y = "Sales")
