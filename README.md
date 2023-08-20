body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
  background-color: #f0f0f0;
}

.converter {
  background-color: #ffffff;
  border-radius: 8px;
  box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
  padding: 20px;
  text-align: center;
}

.input-container {
  margin: 10px 0;
}

label {
  display: block;
  font-weight: bold;
}

input {
  width: 100%;
  padding: 8px;
  border: 1px solid #ccc;
  border-radius: 4px;
}

h2 {
  margin-top: 0;
}

/* Responsive adjustments */
@media (max-width: 400px) {
  .input-container {
    display: flex;
    flex-direction: column;
  }

  input {
    margin-top: 5px;
  }
}
