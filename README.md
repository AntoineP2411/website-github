# website-github

const newCouple = 'Julia et Antoine';

// Jul 04, 2026
const weddingDate = new Date(2026, 07, 04);

// Wedding venue: https://goo.gl/maps/5z5xX2hTYzU8VGEJ9
const weddingVenue = new Location('Lieu-dit Botier, Quessoy, Côtes d'Armor');

(function() {
    newCouple.willTieKnot(weddingDate);

    // your presence is requested
    (new Wedding()).acceptInvitation(
        window.open('https://sonali.netlify.app/')
    );
})();

