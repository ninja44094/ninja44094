onst pokemonIndices = [#, #, #, #, #,];

pokemonIndices.forEach(index => {
    this.scene.gameData.starterData[index] = {
        abilityAttr: 7,
        candyCount: 200,
        eggMoves: 15,
        friendship: 90,
        passiveAttr: 3,
        valueReduction: 2
    };

    this.scene.gameData.dexData[index] = {
        caughtAttr: 255n,
        ivs: [31, 31, 31, 31, 31, 31],
        seenAttr: 479n,
        caughtCount: 69,
        hatchedCount: 69,
        seenCount: 69,
        natureAttr: 67108862
    };

    console.log(`Attributes updated for Pokémon ${index}.`);
});
