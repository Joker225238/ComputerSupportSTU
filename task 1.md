# 1. Create variables with all atomic types
char_var <- "Hello"
num_var <- 3.14
int_var <- 42L
complex_var <- 1 + 2i
logical_var <- TRUE

# 2. Create the specified vectors
seq_vector <- seq(5, 75)                # Sequence from 5 to 75
num_vector <- c(3.14, 2.71, 0, 13)      # Numeric vector
true_vector <- rep(TRUE, 100)            # Vector with 100 TRUE values

# 3. Create the specified matrix
my_matrix <- matrix(c(12, 34, 87,
                      -12, -12.1, 0,
                      3.6, 0.5, 1.3), 
                    nrow = 3, byrow = TRUE)

# 4. Create a list with all atomic types
my_list <- list(char = char_var, 
                num = num_var, 
                int = int_var, 
                complex = complex_var, 
                logical = logical_var)

# 5. Create a factor with 3 levels
my_factor <- factor(c("infant", "child", "adult"))

# 6. Create a data frame
my_data_frame <- data.frame(
  Name = c("Alice", "Bob", "Charlie"),
  Age = c(5, 10, 30),
  Height = c(1.2, 1.5, 1.8)
)

# 7. Change column names of the data frame
colnames(my_data_frame) <- c("Person_Name", "Person_Age", "Person_Height")

# Output the results
print(seq_vector)
print(num_vector)
print(true_vector)
print(my_matrix)
print(my_list)
print(my_factor)
print(my_data_frame)

