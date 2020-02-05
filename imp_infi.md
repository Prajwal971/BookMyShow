
    array.forEach(item => {
        if (item.toLowerCase().indexOf(search_term) !== -1) {
            // console.log(item);
            // flag =    true; 
            matched_terms.push(item);
        }

    })