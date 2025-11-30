# website-github

const newCouple = 'Sonali & Gagan';

// Nov 29, 2020
const weddingDate = new Date(2020, 11, 29);

// Wedding venue: https://goo.gl/maps/5z5xX2hTYzU8VGEJ9
const weddingVenue = new Location('Ashirwad Garden, Ranchi');

(function() {
    newCouple.willTieKnot(weddingDate);

    // your presence is requested
    (new Wedding()).acceptInvitation(
        window.open('https://sonali.netlify.app/')
    );
})();

