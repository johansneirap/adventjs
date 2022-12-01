function wrapping(gifts) {
  const wrapLength = len => '*'.repeat(len + 2)
  const wrappedGift = gift => `${ wrapLength(gift.length) }\n*${ gift }*\n${ wrapLength(gift.length) }`
  
  return gifts.map( gift => wrappedGift(gift))
}
