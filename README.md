# website-github

const newCouple = 'Julia et Antoine';

// Jul 04, 2026
const weddingDate = new Date(2026, 07, 04);

// Wedding venue: https://www.google.fr/maps/place/Botier,+22120+Quessoy/@48.431711,-2.6851607,15z/data=!4m6!3m5!1s0x480e19466bc2972d:0x4f787837f125d1df!8m2!3d48.431712!4d-2.674861!16s%2Fg%2F1v9tz8y3?entry=ttu&g_ep=EgoyMDI1MTEyMy4xIKXMDSoASAFQAw%3D%3D
const weddingVenue = new Location('Lieu-dit Botier, Quessoy, Côtes d'Armor');

(function() {
    newCouple.willTieKnot(weddingDate);

    // your presence is requested
    (new Wedding()).acceptInvitation(
        window.open('https://sonali.netlify.app/')
    );
})();

