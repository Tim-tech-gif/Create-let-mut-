# Create-let-mut-
fn gray(n: u8) -> Vec&lt;String> {     if n == 0 {         return vec![String::from("")];     }      // Start with 1-bit gray code     let mut result = vec![String::from("0"), String::from("1")];      // Build for n bits     for i in 2..=n {
