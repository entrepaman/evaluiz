# Reviews.css

### code

{% code-tabs %}
{% code-tabs-item title="/src/components/Reviews/Reviews.css" %}
```css
@import url('https://fonts.googleapis.com/css?family=Exo+2:400,700');

.Rating {
    background-color: #fff;
    margin: 0 auto;
    width: 50%;
    padding: 2em 2em;
    border-radius: 3px;
    text-align: center;
    margin-top: 4em;
}

.Rating > span {
    display: block;
    margin-bottom: 22px;
}

.Rating span {
    font-size: 3rem;
    color: #f9a825;
}

.Rating p {
    font-size: 1.2rem;
    margin: 0;
    margin-bottom: 1em;
}

.Rating textarea {
    width: 85%;
    height: 150px;
    border: none;
    background-color: #eee;
    padding: 10px 20px;
    outline: none;
    border-radius: 3px;
    font-size: 1rem;
    font-family: 'Righteous';
    margin: 1em 0;
}

.OlderRatingReviews {
    background-color: #64b5f6;
    padding: 18px 30px 1px 40px;
    border-radius: 3px;
    margin-bottom: 2em;
    text-align: left;
    border-left: 6px solid #1565c0;
}

.OlderRatingReviews .Title {
    font-weight: 700;
}

.OlderRatingReviews p {
    margin: 0;
    font-family: 'Exo 2', sans-serif;
}

.OlderRating {
    margin: 1em !important;
}

.OlderReview {
    margin: 1em !important;
}

.Thanks {
    background-color: #fff;
    margin: 0 auto;
    width: 60%;
    padding: 2em 2em;
    font-size: 1.5rem;
    border-radius: 3px;
}

@media (max-width: 600px) {
    .Rating {
        width: 80%;
    }
}
```
{% endcode-tabs-item %}
{% endcode-tabs %}

