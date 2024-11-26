import streamlit as st

# Title of the Streamlit app
st.title("My Student Biography")

# Section for personal details
st.header("About Me")
st.write("""
Hello! My name is **[Your Name]**. I am a student at **[Your University]**. I am currently studying **[Your Major]**.
I am passionate about learning and exploring new things in the field of **[Your Field of Interest]**.
""")

# Personal Details
st.subheader("Personal Details")
name = "[Your Name]"
age = "[Your Age]"
university = "[Your University]"
major = "[Your Major]"
year = "[Current Year of Study]"
location = "[Your Location]"

st.write(f"**Name:** {name}")
st.write(f"**Age:** {age}")
st.write(f"**University:** {university}")
st.write(f"**Major:** {major}")
st.write(f"**Year of Study:** {year}")
st.write(f"**Location:** {location}")

# Section for Academic Interests
st.header("Academic Interests")
st.write("""
I have a strong interest in:
- **[Interest 1]**: Description of your interest.
- **[Interest 2]**: Description of your interest.
- **[Interest 3]**: Description of your interest.

I am particularly excited about learning more about these topics and exploring related opportunities.
""")

# Section for Hobbies and Activities
st.header("Hobbies & Extracurricular Activities")
st.write("""
Outside of my academic life, I enjoy:
- **[Hobby 1]**: Description of your hobby.
- **[Hobby 2]**: Description of your hobby.
- **[Hobby 3]**: Description of your hobby.

These activities help me develop both personally and professionally.
""")

# Section for Future Goals
st.header("Future Goals")
st.write("""
In the future, I aim to:
- **[Goal 1]**: Description of your goal.
- **[Goal 2]**: Description of your goal.
- **[Goal 3]**: Description of your goal.

I am determined to achieve these goals and make a positive impact in my field.
""")

# Optional: Add an Image (e.g., a profile picture or relevant photo)
st.header("A Picture of Me")
st.image("your_image.jpg", caption="Your Name", use_column_width=True)

# Footer
st.write("Thank you for visiting my student biography!")


