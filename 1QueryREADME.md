1. Problem Statement: Customer Query Classification Using Prompt Engineering
An e-commerce company receives numerous customer queries related to orders,
deliveries, payments, refunds, cancellations, and product defects. Your task is to design
an effective prompt that classifies each customer query into the appropriate predefined
category.
Input: A customer query in natural language.
Output: A single word representing the category of the query.
Categories:
• Delivery
• Shipping
• Refund
• Payment
• Cancellation
• Defect
• Return
• Account
• Unknown
Examples:

Input Query Expected Output

My order has not arrived yet. Delivery
My package is stuck in transit. Shipping
I haven't received my money back. Refund
Money was deducted twice from my account. Payment
I want to cancel my order. Cancellation
The product I received is broken. Defect
I want to send this product back. Return
I cannot log in to my account. Account
What is the capital of India? Unknown

Constraint: The output must contain exactly one category word, without explanations,
punctuation, or additional text.
