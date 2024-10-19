### Step 1 - Git clone

```
git clone https://github.com/tsengel11/project_one_app
```

### Step 2 - Install required packages. (use pip if your local not support pip3)

```
pip3 install --upgrade openai
```

```
pip3 install streamlit
```

### Step 3 - Update OpenAI API Key & Assistant ID

Modify `/.streamlit/secrets.toml` to use your own [OpenAI API key](https://platform.openai.com/account/api-keys), and [assistant_id](https://platform.openai.com/assistants)

And rename it to `/.streamlit/secrets.toml`.

## Example usage

```
streamlit run app.py
```